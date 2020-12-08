# EE629 Real-time video streaming based on Flusk

**Description:** In this project, I use a normal Raspberry Pi camera and stream the video to the Web page which implemented by a web server. I also bought a DHT11 and want to put temperature and humidity on the same page but it occoured errors I didn't figure it out.

**File location:**

               ├── camera_pi.py
               ├── app.py
               ├── templates
               |     ├── index.html
               └── static
                     ├── style.css


**Video streaming server created:**

<img src="https://github.com/JiaqiTu/EE629-IOT/blob/master/images/live_stream.png" width = "300" height = "200" alt="1" align=center />


**Temperature and humidity monitor:**

rpi_tempmon.py is a python script to display the CPU & GPU temperature of Raspberry Pi. I want to use rpi_tempmon.py to generate the real time temperatures & graphics and put on to the website. 
https://github.com/gavinlyonsrepo/raspberrypi_tempmon
```
sudo pip3 install rpi_tempmon.py
```





