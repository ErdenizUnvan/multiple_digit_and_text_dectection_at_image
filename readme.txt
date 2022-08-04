This app is developed by Erdeniz Unvan for image and text detection of Rocket League online mutiplayer game

The CNN model has been designed and executed at the app according to the properties and background for the game.

In order to use the pytesseract python library, first install tesseract-ocr-w64-setup-v4.0.0-beta.4.20180912.exe file with all language packages
and choose the directory at where it is installed at your computer as seen below:

pytesseract.pytesseract.tesseract_cmd = r"C:\Program Files (x86)\Tesseract-OCR\tesseract.exe"

This is an example from my own computer. You will use this code at our app. Modify it if necessary.

The photos at the game are either black background and white number or the other way around. All pics from the game are out of focus. So 
we first we work with creating focus and turning dark grey to black and light grey to white. 

If you wish to use this code for working with photos from any other example, you should modify the code.

You can also modify the tesseract for which language of photo you are going to work with.

Enjoy,

Erdeniz Unvan

