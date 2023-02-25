# Face-Recognition-Attendance-Management-System
Face-Recognition-Attendance-Management-System

![87268584](https://user-images.githubusercontent.com/87268584/221363578-84e7769c-fca3-47a2-991b-05776fcd52c7.jpg)

# Code Requirements
Opencv(pip install opencv-python)
Tkinter(Available in python)
PIL (pip install Pillow)
Pandas(pip install pandas)

# What steps you have to follow??
Download my Repository
Create a TrainingImage folder in a project.
Open a AMS_Run.py and change the all paths with your system path
Run AMS_Run.py.

#Project Structure
After run you need to give your face data to system so enter your ID and name in box than click on Take Images button.
It will collect 200 images of your faces, it save a images in TrainingImage folder
After that we need to train a model(for train a model click on Train Image button.
It will take 5-10 minutes for training(for 10 person data).
After training click on Automatic Attendance ,it can fill attendance by your face using our trained model (model will save in TrainingImageLabel )
it will create .csv file of attendance according to time & subject.
You can store data in database (install wampserver),change the DB name according to your in AMS_Run.py.
Manually Fill Attendance Button in UI is for fill a manually attendance (without facce recognition),it's also create a .csv and store in a database.

# Screenshots
# Basic UI
![image](https://user-images.githubusercontent.com/87268584/221363744-f1a9ec6b-2c3b-4da0-b135-48f26381d613.png)
![Take Image](https://user-images.githubusercontent.com/87268584/221363799-6094dbcd-51b2-4004-ad0e-5ae1fd8f438e.png)

![trainned](https://user-images.githubusercontent.com/87268584/221363841-11883bff-08fa-4125-bc09-fa716c632ab8.png)


# When it Recognises me

![Automatic](https://user-images.githubusercontent.com/87268584/221363846-f8bb4d7a-e454-4c79-8597-11ffee154c8f.png)

# While filling automatic attendance
![Attendance](https://user-images.githubusercontent.com/87268584/221363933-a3eddceb-7ced-4f59-bce7-9705870d4922.png)


# Notes
It will require high processing power(I have 8 GB RAM)
Noisy image can reduce the accuracy, so quality of images should be good.





#When it Recognises me
![Uploading Automatic.png…]()
