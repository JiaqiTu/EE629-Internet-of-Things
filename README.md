# Project: Real-time Video Streaming Based on Flask

**Description:** In this project, I use a normal Raspberry Pi camera and stream the video to the Web page which implemented by a web server.

**File location:** Flask uses the directory ```app.py``` located as the general directory. By default, static valuable is in the ```static``` directory, and template is in the ```templates``` directory.

               ├── camera_pi.py
               ├── app.py
               ├── templates
               |     ├── index.html
               └── static
                     ├── style.css


**Video streaming server created:**

<img src="https://github.com/JiaqiTu/EE629-IOT/blob/master/images/live_stream.png" width = "300" height = "200" alt="1" align=center />


**Temperature and humidity monitor:**

 I also bought a DHT11 and in ```project_improvement``` directory I put temperature and humidity on the website.
 
 Install the DHT Package:
 
 ```sudo pip install Adafruit_Python_DHT```
 
 Result:
```
root@localhost:~# sudo python AdafruitDHT.py 11 4
Temp=25.0   Humidity=46%
```

<img src="https://github.com/JiaqiTu/EE629-IOT/blob/master/images/livevideo2.png" width = "400" height = "300" alt="2" align=center />



