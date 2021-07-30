# LICENSE-PLATE-RECOGNITION-SYSTEM
 The license plate reading system is written in C language.
 
 In this project, license plate recognition system is made by using image processing techniques.

The recognition system consists of 4 stages.
1. stage = The vehicle moves in front of the camera.
2. stage = Camera captures the car.
3. stage = The picture of the taken plate is sent to the computer. Here, the picture goes through these algorithms respectively Grayscale, Binary, Median, Thresholding, Sobell Edge Detection, Find Plaque, Crop Plaque. Thus, the outer frame of the plate is detected. The reason why the plate can be easily detected is the color perception of the plate itself. Thanks to algorithms, it detects the black-white ratio of the plate. The characters on the plate defined later are defined. In this way, the characters on it are printed.

Choose the picture -> Grayscale Algorithm -> Binary Algorithm -> Median Algorithm -> Thresholding Algorithm -> Sobell Edge Detection Algorithm -> Find Plaque (Rectangle) -> Crop Plaque (Rectangle) -> Reading plate(writing)

4. stage = The interface program written for the system must be installed on the computer. In order for this interface to work, .Net Framework infrastructure must be installed on the computer.
 
In this software, Tesseract OCR is used to read the characters on the plate. When the license plate recognition results were examined, it was confirmed with the applications that the reading speed and accuracy rates of the license plates were improved. The 88% correct reading of the plates supports this situation with a 98% success rate.
 
###################################################################################################
Bu projede görüntü işlemleri teknikleri kullanılarak plaka tanıma sistemi yapılmaktadır. 

Tanıma sistemi 4 aşamadan oluşmaktadır. 
1. aşama= Araç kameranın karşısına geçer.
2. aşama = Kamera arabayı çeker.
3. aşama = Çekilen plakanın resmi bilgisayara gönderilir. Burada resim  sırasıyla Grayscale, Binary, Median, Thresholding, Sobell Edge Detection, Find Plaque, Crop Plaque bu algortimalardan geçer. Böylelikle plakanın dış çerçevesi algılanır. Plakanın rahatlıkla algılanmasının sebebi plakanın kendi içinde renk algısının olmasıdır. Algoritmalar sayesinde Plakanın siyah-beyaz oranını algılar. Sonrası tanımlanan plakanın üzerinde bulunan karakterler tanımlanır. Bu şekilde üzerinde ki karakterler yazdırılır.
4.aşama = Sistem için yazılan arayüz programı bilgisayarda kurulu olmalıdır. Bu arayüzün çalışabilmesi için bilgisayarda .Net Framework altyapısının kurulu olması gerekmektedir. 

Bu yazılımda Tesseract OCR, plaka üzerinde bulunan karakterleri okumak için kullanılır. Plaka tanıma sonuçları incelendiğinde, plakaların okuma hızı ve doğruluk oranlarının iyileştirildiği uygulamalarla teyit edilmiştir. Plakaların %88,1 doğru okunması %98 başarı oranı ile bu durumu desteklemektedir.
