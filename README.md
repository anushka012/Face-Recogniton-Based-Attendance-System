# Face Recognition Project
This repository contains code for facial recognition using OpenCV and python with a Tkinter GUI interface. If you want to test the code then run the train.py file
The technology used: -OpenCV (Opensource Computer Vision) -Python -Tkinter GUI interface
Here I am working on a Face recognition based Attendance Management System by using OpenCV(Python). One can mark their attendance by simply facing the camera. And their attendance is saved in the CSV file.


## How it works :
When we run train.py a window is opened and ask for entering Id and Enter Name. After entering the name and id then we have to click the Take Images button. By clicking Take Images camera of the running computer is opened and it starts taking image samples of a person. This Id and Name is stored in the folder StudentDetails and the file name is StudentDetails.csv. It takes 60 images as samples and stores them in the folder TrainingImage.After completion, it notifies that images are saved. After taking the image sample we have to click the Train Image button. Now it takes a few seconds to train the machine for the images that are taken by clicking the Take Image button and creating a Trainner.yml file and store in the TrainingImageLabel folder. Now all initial setups are done. By clicking the Track Image button camera of the running machine is opened again. If the face is recognised by the system then the Id and Name of the person is shown on Image. Press Q(or q) to quit this window. After quitting it attendance of a person will be stored in the Attendance folder as a csv file with name, id, date and time and it is also available in the window.

## Credits:
### Anushka Agarwal
### Anushka S
### Sarthak Gupta
