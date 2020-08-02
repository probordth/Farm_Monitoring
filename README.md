# Iot_Based Farm Monitoring

In brief, this project was designed to enhance or improve the awareness of a farmer towards his/her agricultural environment. In the present, many manual monitoring methods do exist within the farming community (e.g. Soil Test Kit). However, they require additional human labour and aren't producing results at real time. Therefore, this proposed monitoring system is a better and efficient method which can be introduced to the farming community and we hope that this will enhance the productivity and awareness within the farming community.

## ***Individual Contribution - Web Platform***

## 1 The User Interface using Node-RED
#### 1.0 Farmer Login
This is the main tab of the UI. A new farmer needs to first register to the sytem using the "Farmer Register" portal. Once registered, he/she can use the login credentials to monitor his/her agricultural environment at real time.

**[*Note : On beforehand, the farmer will have to place the outdoor device with an internet connection*]**

![farmer login](https://user-images.githubusercontent.com/68633899/88427097-eb8dee00-ce0f-11ea-8bad-f2f99ce4ab12.JPG)




#### 1.1 Admin Settings

This is the admin settings of the UI. The purpose of this tab is that an "admin" in the system, gets to monitor and track all the registered farmers and the devices which are currently active within the system. Using real time GPS co-ordinates, the admin can track each device within it system.

A Small Note : The farmer capacity within the system can be increased according to the requirement.

![admin](https://user-images.githubusercontent.com/68633899/88430515-3448a580-ce16-11ea-9a22-ce7a8b1080f0.JPG)




#### 1.2 Database

The sensor data are stored in a Database (SQLite) for monitoring purposes. The way this works is that using SQL commans in JS, the sensor data values are updated in the UI and database simultaneously. 

Likewise, if we need to extract stored sensor data from the database, for some useful work (e.g to view the sensor data history) we use SQL commands in JS to extract the necessary details.

**The system is programmed in a way that every registered farmer will have his own database table. To differentiate between the farmers, each table in the database is created using a unique ID for each farmer.**



