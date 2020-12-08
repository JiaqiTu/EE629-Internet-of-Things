# EE629 Real-time video streaming based on Flusk

**Description:** In this project, I use a normal Raspberry Pi camera and stream the video to the Web page which implemented by a web server.

**File location:** Flask uses the directory ```app.py``` located as the general directory. By default, static in the static directory, and templates in the templates directory.

               ├── camera_pi.py
               ├── app.py
               ├── templates
               |     ├── index.html
               └── static
                     ├── style.css


**Video streaming server created:**

<img src="https://github.com/JiaqiTu/EE629-IOT/blob/master/images/live_stream.png" width = "300" height = "200" alt="1" align=center />


**Temperature and humidity monitor:**

 I also bought a DHT11 and want to put temperature and humidity on the same page but it occoured errors I didn't figure it out.

```
sudo pip3 install rpi_tempmon.py
```





