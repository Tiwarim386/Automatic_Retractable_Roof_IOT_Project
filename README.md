# Automatic_Retractable_Roof_IOT_Project

Used C++,IBM Watson IOT modules, Rain sensor, Node RED, Arduino uno, Blynk app to build an Automatic Retractable Roof.

Functionalities:

1. Rain sensor detects rain droplets and sends signal to arduino uno which instructs the motor to automatically shuts the roof over perishable items under it. 

2. When Rain stops the rain sensor instructs the arduino uno to open the roof because the perishable items might need sunshine.

3. Using Watson IOT modules, the roof closing/opening activity used to reach the user in form of an email.

4. The weather status was fetched from Weather API and user was asked for input incase of an upcoming rain.

5. The user was provided an Blynk app with two functionalities- Close roof/ Open roof. It allowed to user to control the roof while being far away.

6. When the user is near he can manually close/open the roof irrespective of rain sensor values using WiFi


       
<p align="center">
  <h3 align="center">  IBM IoT Cloud real time values </h3>
</p>
<p align="center">
  <img width="460" height="300" src="https://github.com/Tiwarim386/Automatic_Retractable_Roof_IOT_Project/blob/master/IBM%20IoT%20Cloud%20(real-time%20values).png">
</p>
<p align="center">
  <h3 align="center">  NodeRed Function Code </h3>
</p>
<p align="center">
  <img width="460" height="300" src="https://github.com/Tiwarim386/Automatic_Retractable_Roof_IOT_Project/blob/master/NodeRed%20Function%20code.png">
</p>
<p align="center">
  <h3 align="center">  NodeRed Flow and Logs </h3>
</p>
<p align="center">
  <img width="460" height="300" src="https://github.com/Tiwarim386/Automatic_Retractable_Roof_IOT_Project/blob/master/NodeRed%20Flow%20and%20logs.png">
</p>
