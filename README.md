# Face-Recognition-Attendance-Management-System
Face-Recognition-Attendance-Management-System

![image](https://user-images.githubusercontent.com/87268584/221373085-0fa8e345-ad2b-440f-b3d6-806641998838.png)



#### Code Requirements

Opencv(pip install opencv-python)

Tkinter(Available in python)

PIL (pip install Pillow)

Pandas(pip install pandas)

pip install opencv-contrib-python --upgrade


#### What steps you have to follow??

Download my Repository

Create a TrainingImage folder in a project.

Open a AMS_Run.py and change the all paths with your system path

Run AMS_Run.py.

#### Project Structure

* After run you need to give your face data to system so enter your ID and name in box than click on Take Images button.
* It will collect 200 images of your faces, it save a images in TrainingImage folder
* After that we need to train a model(for train a model click on Train Image button.
* It will take 5-10 minutes for training(for 10 person data).
* After training click on Automatic Attendance ,it can fill attendance by your face using our trained model (model will save in TrainingImageLabel )
* it will create .csv file of attendance according to time & subject.
* You can store data in database (install wampserver),change the DB name according to your in AMS_Run.py.
* Manually Fill Attendance Button in UI is for fill a manually attendance (without facce recognition),it's also create a .csv and store in a database.

# Screenshots
# Basic UI

![image](https://user-images.githubusercontent.com/87268584/221373654-b59471c8-38eb-437e-8219-280715da1286.png)


![image](https://user-images.githubusercontent.com/87268584/221373690-593d7b54-7083-4d68-8a51-4d70f7076ecb.png)

![image](https://user-images.githubusercontent.com/87268584/221373773-dccd9477-e818-47df-af14-21f60d47215a.png)


![image](https://user-images.githubusercontent.com/87268584/221373811-3faf8b7f-224e-4c98-bbb2-57646f59591f.png)

![image](https://user-images.githubusercontent.com/87268584/221373865-7fd3855d-6dec-4d4d-bde3-d0759a9afb50.png)



# When it Recognises me

![Automatic](https://user-images.githubusercontent.com/87268584/221363846-f8bb4d7a-e454-4c79-8597-11ffee154c8f.png)

# While filling automatic attendance

![Attendance](https://user-images.githubusercontent.com/87268584/221363933-a3eddceb-7ced-4f59-bce7-9705870d4922.png)


# Notes

It will require high processing power(I have 8 GB RAM)
Noisy image can reduce the accuracy, so quality of images should be good.

* if gives error then
  write
  pip install opencv-contrib-python --user
  it will work fine for cv2.face.LBPHFaceRecognizer_create();




#When it Recognises me
![Uploading Automatic.png…]()
