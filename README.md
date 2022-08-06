# Smart-Methods-internship-IOT-week-4  
This is the work of week 2 of the internship for internet of things track which include:  
1- create a webpage that get the value of a sensor  
&emsp;1.1- it will use GET method  
&emsp;1.2- the value will be of an integer type  
2- create a database of any type  
&emsp;2.1- to create mySQL database table for the sensor:  
&emsp;&emsp;CREATE TABLE `sensor` (  
&emsp;&emsp;&emsp;`id` int NOT NULL AUTO_INCREMENT,  
&emsp;&emsp;&emsp;`value` int NOT NULL,  
&emsp;&emsp;&emsp;`date` timestamp NOT NULL DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP,  
&emsp;&emsp;&emsp;PRIMARY KEY (`id`));  
3- create a webpage that save a sensor value in a database  
&emsp;3.1- will get the value from the ESP32 with GET method  
&emsp;3.2- the value will be in $_GET
