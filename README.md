# PROJECT-1-UEMK-HANDWRITING RECOGNIZER :star_struck:

[![Generic badge](https://img.shields.io/badge/advance-Python3-yellowgreen)](https://shields.io/) 

***This new Web application is created by Biswarup Bhattacharjee, student of BTECH, in University of Engineering and Management, Kolkata.***

**Email Id: bbiswa471@gmail.com.** 

**Contact No: 916290272740.** 

[![Generic badge](https://img.shields.io/badge/contact%20me-facebook-blue)](https://www.facebook.com/biswarup.bhattacharjee.5811) [![Generic badge](https://img.shields.io/badge/visit%20my%20projects%20-github-brightgreen)](https://github.com/biswa2210)

## About :point_down: 
I have a handwritten recognizer for recognising both handwritten text and OCR. Python-tesseract is used to recognize and read the text. In handwriting recognition (HWR) the device interprets the user's handwritten characters or words into a format that the computer understands (e.g., Unicode text). The input can be from paper documents, images, touch-screens and other devices. There are many levels of HWR, starting from the recognition of simplified individual characters to the recognition of whole words and sentences of cursive handwriting. Character recognition often involves scanning a form or document. This means the individual characters contained in the scanned image will need to be extracted. After the extraction of individual characters occurs, a recognition engine is used to identify the corresponding character. OCR systems consist of following major stages : • Classification • Post-processing • Feature Extraction. This Handwriting recognition is used for numerous applications such as : reading postal addresses, bank check amounts, and forms. Furthermore, OCR plays an important role for digital libraries, allowing the entry of image textual information into computers by digitization, image restoration, and recognition methods.

:point_right: [click here to read Project1 Research Paper](https://github.com/biswa2210/PROJECT-1-UEMK/blob/master/3rdSemProject1ResearchPaper.pdf)<br>
:point_right: [click here to see Project1 PowerPoint Presentation](https://drive.google.com/file/d/16rftW-uNvv6KIOxdEnpGsC0js1hqR0Fi/view)<br>
:point_right: [click here to view or download Project1 Demo Video](https://drive.google.com/file/d/1tpUvWbsJbWVD_u-boNK_VNQJz8GSQ5fi/view)
## Working Principle :point_down:
Let me describe the main working part of our project. Here main three parts are present. First one is GUI part which means the Graphical User Interface part of our project. Second one is Handwritten Digit Recognition part. It contains also a GUI part that is Handwritten Recognition GUI and second one is functionality part. In this functionality part two functionalities are present, first one is pictorial detection functionality that recognizes Handwritten digits from an image and second one is the live detection functionality that recognizes handwritten digits from a video. Let us come to the ocr part of our project. Ocr stands for Optical Character Recognition , here we use Tesseract algorithm to detect handwritten characters as well as type written character also. In this part after recognizing the characters it will pronunciated by python text to speech library that is the pyttsx3 library in python. Let me deep dive into the GUI part. GUI is basically type of user interface through which users interact with electronic devices via visual indicater representation . It allows the user of a computer to communicate with the computer by moving a pointer around on a screen and clicking a button. In our project it is created by Tkinter package In python.This has a developer section which is also made by Tkinter.In our project handwritten digit recognition part is made by the concept of deep learning. Basically deep learning is a subset of machine learning. In this part we will create a deep learning model using the MNIST dataset which is present in the keras model in python. The set of images in the MNIST dataset is a combination of two of NIST's databases. The NIST databases are special database 1 and special database 3.It consists of digits written by High School students and employees of United States Census Bureau. The MNIST dataset contains total 70000 images in those 60000 images are training images and 10000 images are testing images. All images are normalized to fit into 28 into 28 pixels. Let us a come to the model creation part. Here we use CNN analysis to create our deep learning model. CNN is basically Convolutional Neural Network. It's used for matrix manipulation or manipulation. The first step of CNN is input image from our MNIST dataset after that it will pass through the Convolutional layers. In our project 64 Convolutional 2 d filters are used . In CNN this part us called feature detecting part or filtering part. After that this filtered image will pass through the neural network.Then generate a fully connected layer and get the output layer. For creating our deep learning model we use the activation function relu that is rectified linear unit in Convolutional 2 d function for solving vanishing gradient problem where the kernel size is 3,3. In the output layer of our model we use softmax activation function in dense function for predicting the multiple outputs. At last for compiling our model we use SGD that is Stochastic Gradient Decent optimzer which is an iterative method for optimizing an objective function with suitable smoothness properties. In browsing image part in our project we use the opencv function in python to recognize input image which is inputted by filedialogue function in Tkinter. This is all about working of Machine learning part of my project.

## Purpose :point_down:
The goal of this project is to create a model that will be able to recognize and determine the handwritten digits from its image by using the concepts of Convolution Neural Network and Optical Character recognition with tesseract-OCR. Though the goal is to create a model which can recognize the digits, it can be extended to letters and an individual’s handwriting. The major goal of the proposed system is understanding Convolutional Neural Network, and applying it to the handwritten recognition system. The another goal of this project is that make a simple user friendly graphical user interface to handle recognizing handwritten digits and OCR, create a developers section in graphical user interface where the all group members details
## Use :point_down:

## Applications and Future Scopes:point_down:
• Postal address reading.<br>
•Check reading.<br>
•Census data collection and processing.<br>
•Image document reading.<br>
•Digitizing old books in editable form.<br>
•Extended research:<br>
   • text to speech conversion (e-book reading).<br>
   •Visually impaired should be able to access computers in their native language.<br>
• Develop an online system for searching hundreds of books over the Web.<br>
• Recognition and retrieval of complex documents (such as camera-based, handwritten, etc.).<br>
• Apply advanced image preprocessing techniques to enhance image quality for large collection of document images.<br>
• Retrieval of documents in presence of OCR errors and scope for hybrid approaches.<br>
## Folder Structure :point_down:
```bash

```                       

## Making :point_down:
I have made this using python3. Now let me come to the OCR part of this project. OCR is basically to recognition and convertion of optical character that is typewritten character into editable data. But using tesseract OCR we can recognise handwriten characters also. Tesseract is an algorithm. In python which is acces by pytesseract module.
Python Tesseract is basically a Optical Character Recognition (OCR) tool in for python . It will recognise or read the text embedded in images. Here it is used as a python script. It is used to load  an image and binarise it then pass it through the tesseract ocr system. Python tesseract will print the recognise txt instead of writing it to a file. At first I had to install the tesseract software in laptop. Then I gave the installation location path to the pytesseract module in python. Then it easily accessed the location and recognise PDF or IMAGES and convert it into text format and save it at our desired file location. Here file location is our project location and the file name is as output.txt. After Recognising hand written characters through OCR is pronounciated by python TEXT TO SPEECH module and translated into HINDI using google trans module in python. 
## Screenshots :point_down: 
<div align="center">
 <a href="hr1.PNG"><img src="hr1.PNG" width="400" height= "250"></a> <a href="hr2.PNG"><img src="hr2.PNG" width="400" height= "250"></a>

<a href="hr3.PNG"><img src="hr3.PNG" width="400" height= "250"></a> <a href="hr4.PNG"><img src="hr4.PNG" width="400" height= "250"></a>

<a href="hr5.PNG"><img src="hr5.PNG" width="400" height= "250"></a> <a href="hr6.PNG"><img src="hr6.PNG" width="400" height= "250"></a>

<a href="hr7.PNG"><img src="hr7.PNG" width="400" height= "250"></a> <a href="hr8.PNG"><img src="hr8.PNG" width="400" height= "250"></a>
</div>

