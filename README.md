# Face-recognition-attendance-system-in-Python-and-OpenCV
# What steps you have to follow??

1- Download or clone my Repository to your device

2- Type pip install -r requirements.txt in command prompt(this will install required package for project)

3- Create a TrainingImage folder in a project folder.

4- Open attendance.py and automaticAttendance.py, change all the path accoriding to your system

5- Run attandance.py file

# Project flow & explaination:-
1- After you run the project you have to register your face so that system can identify you, so click on register new student

2- After you click a small window will pop up in that you have to enter you ID and name and then click on Take Image button

3- After clicking Take Image button A camera window will pop up and it will detect your Face and take upto 50 Images(you can change the number of Image it can take) and stored in the folder named TrainingImage. more you give the image to system, the better it will perform while recognising the face.

4- Then you have to click on Train Image button, It will train the model and convert all the Image into numeric format so that computer can understand. we are training the image so that next time when we will show the same face to the computer it will easily identify the face.

5- It will take some time(depends on you system).

6- After training model click on Automatic Attendance ,you have to enter the subject name and then it can fill attendace by your face using our trained model.

7- it will create .csv file for every subject you enter and seperate every .csv file accoriding the subject

8- You can view the attendance after clicking View Attendance button. It will show record in tabular format.
