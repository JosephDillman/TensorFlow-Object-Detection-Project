# TensorFlow-Object-Detection-Program
For Eduhacks 2017 my team and I decided to use the TensorFlow machine learning python library in order to identify objects through a devices webcam, translate the name of object into a desired language, and attempt to teach the user to learn the vocabulary of the new language.

My team and I successfully built a very basic script that allows users to choose a language (fr = french, es = spanish, ...etc) then point their webcam at an object, attempt to input the translated name of the object in their desired language, and recieve a point if the translation was correct. The script (only the script and not the relevant TensorFlow files) for the full translation project can be found on my **partners github** https://github.com/SinaKhalili/LinguaLook however this repo doesn't include the screenshots from this repo or the object detection files.

What I have posted on **this repository** includes the TensorFlow object detection files and a script that initiates the object detection with the names printed on a box around each object. Example screenshots of the program working are included.

**This program was created following an online tutorial https://www.youtube.com/watch?v=COlbP62-B-U**

**To get the script running**
- find _run.py_ in the object detection folder, this is the source code to run
- I have python 3.5.2 64bit with TensorFlow Installed (must be 64 bit)
- pillow, lxml, jupyter, matplotlib, opencv imported 
- protoc 3.4.0 downloaded and run into the object detection folder
