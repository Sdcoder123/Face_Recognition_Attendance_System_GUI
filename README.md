# Face_Recognition_Attendance_System_GUI
A python GUI integrated attendance system using face recognition to take attendance of the user

In this project i have made desktop application that recognize the user and help the user to give the attendance.
So in this project, I have made an attendance system which takes attendance by using face recognition technique. I have also intergrated it with GUI (Graphical user interface) so it can be easy to use by anyone. Now building the frame-work i have used the tkinter.The techs i have used in my project:

# Techs:

    A. tkinter for whole GUI
    B. OpenCV for taking images and face recognition (cv2.face.LBPHFaceRecognizer_create())
    C. CSV, Numpy, Pandas, datetime etc. for other purposes.

# Features it has:

   1. Easy to use with interactive GUI support.
   2. Password protection for new person registration.
   3. Creates/Updates CSV file for deatils of students on registration.
   4. Creates a new CSV file everyday for attendance and marks attendance with proper date and time.
   5. Displays live attendance updates for the day on the main screen in tabular format with Id, name, date and time.

# Instructions to be followed to use this GUI:
( At first we have to run the main.py with all necessary files)

1. Now for the new user on our desktop app he or she have to register there by providing their id and name.
2. After that they have to go to the take images section and there the camera will be popped down and have to wait for couple of seconds. 
3. Then the camera will be closed and the user have to save the profile, by putting the default password that is sdnew ,now the user is registered
4. Now while giving the attendance once have to make sure that he or she have to be registered first.
5. So after going to the registered section one should have to stay front of the camera, and press the attendance system tab.
6. After that the camera will be appeared in front of the user and it will check if you are registered or not , if you are registered then it will show your name in  the camera.
7. Then the user have to press q in the keyboard to get the attendance. Now the user can see his/her name in the attendance sheet of the screen there the ID , name ,Time will be shown.

# Password related query:

1. The default password is ‘sdnew’ it will be used while saving a new user.
2. Now the password is saved in the psd.txt of trainingImageLabel.
3. Now if anyone wants to change the password, he or she can do it by clicking the help box in the GUI.
  # Screenshot of help box
  ![oi](https://user-images.githubusercontent.com/98347730/170689855-163f85eb-f90a-49d2-be62-c9b60cc1a641.png)

4. There you will be asked to put the old password and the new password and the confirm one after that your password will be saved in our txt file.

# Important things to be remembered:

1. The haarcascade_frontalface_default.xml should be there in the Face recognition folder.
2. While saving the password we have to put the default password that is 'sdnew' to save the user.
3. Now while taking attendance user have to press q after seeing him/her in the camera to entry their names in the attendance sheet.

# UI Screenshot:

![Ui](https://user-images.githubusercontent.com/98347730/170689101-bf6bde05-9c6e-4078-ba0a-3e9871c8ad9e.png)

# Default Password:
![d](https://user-images.githubusercontent.com/98347730/170689644-509a837a-1395-4718-9fe1-56df495ee621.png)

# Demo Video:
https://drive.google.com/file/d/1-31FaaAt-T9cbKrujSuAyh5lXkryrGJC/view?usp=drive_link








