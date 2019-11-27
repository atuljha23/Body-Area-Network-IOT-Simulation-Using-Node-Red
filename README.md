# Body Area Network IoT Simulation Using Node-Red
Simulating the Body-Area-Network Sensors in real-time on Node-Red.

**List of Sensors**
1. Blood Pressure Sensor
2. Heart Rate Sensor
3. Digital Insulin Sensor
4. Oxymeter
5. Respiratory Sensor
6. Temperature Sensor
7. Blood-pH Level
8. Hemoglobin Level

**How to Run?**

- Install Node Red
`sudo npm install -g --unsafe-perm node-red`
- Import Main Node.json on Node-Red.
- Change Certificates of AWS (Generate from AWS IOT Dashboard.)
- Change MQTT Server Details and MQTT Topic Accordingly.
- Change S3 Node Details.
- Deploy.
- Dashboard can be accessed over http://127.0.0.1:1880/ui/
- Android App Source Code is provided build it on Android Studio and Generate the APK.


** Node-Red Flow**

![Node-Red Flow](https://raw.githubusercontent.com/atuljha23/Body-Area-Network-IOT-Simulation-Using-Node-Red/master/Main%20Node.png)

** Dashboard Android App** 
![Android App](https://raw.githubusercontent.com/atuljha23/Body-Area-Network-IOT-Simulation-Using-Node-Red/master/Android%20App.png)

**Flow Diagram** 
![Android App](https://raw.githubusercontent.com/atuljha23/Body-Area-Network-IOT-Simulation-Using-Node-Red/master/Flow%20Diagram.png)

**References**
-  AWS IoT Simulation: https://www.youtube.com/watch?v=beoTMtpvQJ8&t=376s
-  AWS IoT Simulation using AWS Lambda: https://aws.amazon.com/blogs/iot/device-simulation-with-aws-iot-and-aws-lambda/
- Journal: https://journals.sagepub.com/doi/pdf/10.1177/1550147718768994

