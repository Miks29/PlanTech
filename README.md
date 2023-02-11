# PlanTech
AN IOT-BASED SMART POT FOR PECHAY WITH ANDROID APP FOR MONITORING ENVIRONMENTAL FACTORS

## Links
- [Contributors](#contributors)
- [What is it?](#1)
- [Main Application](#main-application)

<a name="1"></a>
## What is it?
PlanTech: An IoT-based Smart Pot for Pechay with Android App for Monitoring
Environmental Factors presents an automated smart pot based on the Internet of Things
(IoT). The system provides a smart means of caring and monitoring the growth of
pechay through the use of automation and IoT technology and to replace conventional
systems where the pechay is watered manually by humans. The system is developed to
grow pechay and be able to provide optimal yields using the smart pot.

- PlanTech was assembled using the main components such as Arduino
Uno as the microcontroller, NodeMCU, connected with sensors such as soil moisture,
water level and photoresistor light sensor. It is also designed with an integrated tank that supplies the desired amount of
water. It also has artificial lighting as an alternative source of light i.e., when plants are
placed indoors.

- The system comes with an android application to monitor the important parameters affecting the growth of pechay such as
soil moisture, sunlight and water pH level and the actuators connected to the system.

# Main Application
Below are the different design interface of the Android Mobile Application developed for PlanTech.

## Login & Sign Up 
The figure below shows the login screen(left) and the sign up screen(right)
<p align="center">
   <img src="https://github.com/Miks29/PlanTech-Mobile-App/blob/30775ca096b80b01e2cc1b392239d94e5443f402/PlanTech_Design/login.png" align=top width=20% height=25%>
   <img src="https://github.com/Miks29/PlanTech-Mobile-App/blob/30775ca096b80b01e2cc1b392239d94e5443f402/PlanTech_Design/sign%20up.png" align=top width=20% height=25%>
</p>

- The user will see the login page of the mobile application upon running it. The user can supply the needed information (email, password) of an existing account.
- If the user don't have an existing account yet, the user can click the "Sign Up" button to create an account. 
- For security purposes, the user needs to verify the email provided where the user will receive an email to verify and use the application successfully afterwards.
- If the user forgot the password of an existing account, the user can click the "Forgot Password" button and enter the related email. An email will be sent to the email provided from the forgot password screen. The user can then reset or change the password.

[Back to Top](#plantech)

## Dashboard
The figure below shows the most important feature of the android application, the
dashboard. The user should see the environmental factors as well as devices’ status
generated by the sensors embedded on the smart pot.
<p align="center">
   <img src="https://github.com/Miks29/PlanTech-Mobile-App/blob/c507151533ee220c7c80a120c88f891fe2220437/PlanTech_Design/dashboard.png" align=top width=20% height=25%>
   <img src="https://github.com/Miks29/PlanTech-Mobile-App/blob/c507151533ee220c7c80a120c88f891fe2220437/PlanTech_Design/dashboard.menu.png" align=top width=20% height=25%>
</p>

- The status will depend on the data under the environmental factors. The sensor
data is presented in percentage values so that the user can easily understand it. 
- For instance, soil moisture level needs to be less than or equal to 48% to activate or turn on
the water pump
- The water tank level needs to be 29% to activate the tank valve
- And brightness level should be dark to turn the LED on.
- From the dashboard screen, the menu options can also be seen (right image), where other features of the android application can be accessible.

[Back to Top](#plantech)

## Profile
The figure below shows the account profile of the user.
<p align="center">
   <img src="https://github.com/Miks29/PlanTech-Mobile-App/blob/c507151533ee220c7c80a120c88f891fe2220437/PlanTech_Design/profile.png" align=top width=20% height=25%>
</p>

- The profile screen interface shows the email used by the user to access the application
- It also shows an option for users to enable / disable push notifications about specific environmental factors and status of the device from the application
- The notification should only work when the switch is ON (activated) and should not show any
notification when the switch is OFF (deactivated).

[Back to Top](#plantech)

## Control Settings
The below figure shows the control settings where the user can choose from automated or manual configuration in using PlanTech directly from the Mobile Application
<p align="center">
   <img src="https://github.com/Miks29/PlanTech-Mobile-App/blob/c507151533ee220c7c80a120c88f891fe2220437/PlanTech_Design/control_settings.png" align=top width=20% height=25%>
</p>

- Clicking the switch above (next to "Automated") into ON (activated) will set the Plantech configuration into Automatic Mode where Plantech will operate automatically depending on the environmental status the sensors are detecting to operate the devices(water pump, artificial lights, water valve)
- Clicking the switch into OFF status (deactivated) means the Plantech will operate manually depending on how the user want the devices to operate from the Android Mobile Application.

[Back to Top](#plantech)

## How to use
The figure below shows the "How to Use" interface from the dashboard menu. It guides the user on how to setup and connect the android mobile application into Plantech
<p align="center">
   <img src="https://github.com/Miks29/PlanTech-Mobile-App/blob/c507151533ee220c7c80a120c88f891fe2220437/PlanTech_Design/setup_guide.png" align=top width=20% height=25%>
</p>

- The interface shows a step-by-step guide for an easy operation on how to use the android mobile application to operate the Plantech Device.

[Back to Top](#plantech)

## Logout
<p align="center">
   <img src="https://github.com/Miks29/PlanTech-Mobile-App/blob/c507151533ee220c7c80a120c88f891fe2220437/PlanTech_Design/logout.png" align=top width=20% height=25%>
</p>

- The user have an option to log out the account and close the application safely.
- If the user wants to use the mobile application again, the user can just access it by logging in again using the existing account.

[Back to Top](#plantech)

<a name="contributors"></a>
## PlanTech : AN IOT-BASED SMART POT FOR PECHAY WITH ANDROID APP FOR MONITORING ENVIRONMENTAL FACTORS
By: 
- De Leon, Ruzzel P.
- Magdaraog, Christian Ferl C.
- Mañosca, Mike Renzo T.
- Mata, Linmark D.
- Viaña, Jeanne Erica B

May, 2022

**A Capstone Project presented to The Faculty of College of Engineering, Architecture, and Technology**

**Rizal Technological University City of Mandaluyong.**

[Back to Top](#plantech)

