![Screenshot (103)](https://github.com/Yazdan-Ghanavati/Human-Pose-Tracking-Package/assets/137007531/eb7a4723-0495-41de-98c6-90f1214bdf1a)# Human-Pose-Tracking-Package

This is a Python-based applications specifcally developed for Windows OS.
So basically, what this software does is to convert a set of particular actions which user will perform in front of the webcam, into a list of selected keys on keyboard or mouse. HPT Package, offers an alternative method of exercising for overweight individuals or those with muscle-related issues. This way the user will be able to experience a real immersion experience in a virtual space.



## Software Env

### Registration
This part is consisted of two forms: Login, SignUp which is directly connected to a SQL database and will analyze the user's data before start of the application.

This is the Sign up page:
![Screenshot (92)](https://github.com/Yazdan-Ghanavati/Human-Pose-Tracking-Package/assets/137007531/0a57528e-9f8c-4feb-934c-d2ae3052abe5)



and this is the Login page:




![Screenshot (93)](https://github.com/Yazdan-Ghanavati/Human-Pose-Tracking-Package/assets/137007531/3a6db416-1161-430b-9e5a-45b25bde4f88)

You can also get access to the forget password form from login page:

![Screenshot (95)](https://github.com/Yazdan-Ghanavati/Human-Pose-Tracking-Package/assets/137007531/87a8065a-be1b-44a3-82d4-05cb6cefb149)


As you can see, there is a guideline in form of recovery steps in order to create a more responsive and safe environment for users who has forgotten their passwords.



### Main Page
![Screenshot (98)](https://github.com/Yazdan-Ghanavati/Human-Pose-Tracking-Package/assets/137007531/b6fa8b0d-9eb2-4318-8a6c-440ff9add0d0)

Well, the main page has 3 parts which will be discussed individually:

#### Action Display
As you can see, user will be able to see the exact way of performing each of the actions through a non-stop gif display with a label of that action. They can easily change that by clicking on the next or previous button.



#### Action Assignment
This section is where user will set a pair of key and action. as it is shown in the picture, some of the actions have interference with each other and if the user choose them, the latest one will have an active status but the rest will become disable.
Actions and keys are displayed in form of two comboxes and user can delete or add their pair by clicking the buttons.



#### Video Capture 
Now as I said before, this software could easily be used in medical and sepcifically rehabilitation institutes. Therefore, by adding this section, user and also the expert could monitor the progress made by the user during a course or set of dates. This way they can change or update the user's actions in order to improve the treatment.




#### Contact us
There is also a contact us page which users can communicate with us through that page as you can see, we published some informations on how they can communicate with us and also some of the basic technologies used in the software for their personal knowledge.

![Screenshot (101)](https://github.com/Yazdan-Ghanavati/Human-Pose-Tracking-Package/assets/137007531/a2c30463-f652-4ee0-b967-22649d02c0ac)



#### Webcam
So the basic logic behind this part is the same as I explained in Human pose tracking project.
This project is based on Google Mediapipe library which allowed us to detect human pose and extract 33 anatomical key points for each user and use them based on their location the webcam frame, in order to convert those actions to keys.

![image](https://github.com/Yazdan-Ghanavati/Pose-Tracking-Module/assets/137007531/d7495723-a1b3-471d-8997-0386925bf711)

##### Calibration
Based on the distance of user from webcam, which is calculated based on the measurement of their eyes focal length, there will be a warning for the user to change their current position. Based on their position, they might be asked to move away, come closer, move right or even left.


![Screenshot (103)](https://github.com/Yazdan-Ghanavati/Human-Pose-Tracking-Package/assets/137007531/6f08289a-e583-43ba-a445-44e2a13651ce)


##### Exit
User can easily close the webcam output by pressing "Q" button manually.

##### Libraries
* OpenCV 4.5.3.56
* Mediapipe 0.8.3
Now connecting the camera with this module, required a third library which was OpenCV. This library is basically developed for Computer Vision purposes and would allow the user to perform Image manipulations in their projects.




