# Methodology 
* The library in the Arduino was loaded and a message was sent to the LCD. Air quality data was collected using the MQ135 sensor. The calibrated sensor made the analog output voltage proportional to the concentration of polluting gases in Parts per Million (ppm).
*  The data is first displayed on the LCD screen and then sent to the Wi-Fi module. 
*  The Wi-Fi module transfers the measured data valve to the server via internet. 
*  The Wi-Fi module is configured to transfer measured data an application on a remote server  called “Thing speak”. 
*  The online application provides global access to measured data via any device that has internet connection capabilities. Data collected from the sensor was converted into a string and used to update the information sent to the remote server.
*  The model was designed using an Arduino Uno microcontroller, Wi-Fi module 8266, MQ135 Gas Sensor and a 16 by 2 liquid crystal display (LCD) Screen. 
* The system overview procedure was classified into Five (5) layers .
*  The first layer was the environmental parameters which are obtained by measurement.
*   The second layer was the study of the characteristics and features of the sensors. 
*   The third layer was the decision making, sensing, measuring, fixing of the threshold valve, periodicity of sensitivity, timing and space. 
*   The fourth layer was the sensor data acquisition. The fifth layer was the ambient intelligence environment.
*    The sensor collected data when operated by the microcontroller and forwarded it over the internet for analysis via the Wi-Fi module.
*   Users were able to monitor measured parameters on their smartphones.



![image](https://user-images.githubusercontent.com/92078769/156720574-8c856104-a4e4-43f4-b91c-eb112af0c03e.png)
