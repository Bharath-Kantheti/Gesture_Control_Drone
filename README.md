# Gesture_Control_Drone
A quadcopter is controlled using hand gestures

The idea of project is to control a Quadcopter with human hand gestures. The basic controls of quadcopter are manipulated based on hand gestures. In the proposed system a person will be wearing a glove and acts a pilot the glove is inculcated with Arduino and MPU6050 sensor where the MPU6050 records the hand gesture and transmits a certain value to the raspberry pi fixed on the drone via a transmitting Lora module. Now a receiving Lora module fixed to raspberry pi on the drone that takes the transmitted info and based on the code written it will send certain value to the Pixhawk flight control and the Fc controls the movement of the drone. Based on the above described method the proposed system works.
	
