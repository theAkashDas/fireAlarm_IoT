# fireAlarm_IoT
Using IoT to detect fire and send alerts to the concerned


#Components Required
1)NodeMCU
2)Flame sensor
3)Jumper wires
4)Buzzer
5)Breadboard

Here we will use IFTTT to send email alerts if there is any flame inside the room.


Make the connections as given in the circuit diagram and copy the complete code given . Then upload the code in NodeMCU using Arduino IDE. The flame sensor is connected at D0 pin to give the digital input to the NodeMCU and Buzzer is connected at D1 pin to get digital output from the NodeMCU. If fire is detected by the flame sensor then it gives “0” and NodeMCU turns on the buzzer and send the alert email to the person using IFTTT automatically.


First include the required libraries and define variables for Wi-Fi SSID and password to initialize the Wi-Fi connection. Since we need to connect to IFTTT server a variable is declared with address of the server. D0 is the pin on NodeMCU for digital input from flame sensor.


This is how a Low cost IoT Fire Alarm system can be made easily just by using three components.
