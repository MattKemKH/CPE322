## Matthew Kemenosh
## Lab 5 - Paho-MQTT
### Installation
Downloaded Mosquitto and added it to my Path. Then I installed paho-mqtt using pip and pulled the latest Paho MQTT client repository from GitHub. I then go to the iot folder and start client.py.
![screenshot of installing)](https://github.com/MattKemKH/CPE322/blob/main/Lab5/pics/paho.png)
### Running sub and pub commands
Next I open 2 terminals. The terminal on the right runs sub.py at first, which is a MQTT subscriber and is listening for new messages. The terminal on the left runs pub.py, which is a MQTT publisher and sends messages which can be recieved by MQTT subscribers. So when pub.py runs on the left terminal, the right terminal prints "paho/test hello". After that I run sub-multiple.py and pub-multiple.py on the right and left terminals respectively. The same behavior as running sub.py and pub.py is seen except for the fact that there are now multiple messages sent and recieved at once. Finally the terminal on the right runs subcpu.py and the one on the left runs pubcpu.py. pubcpu.py periodically publishes my CPU usage which is then recieved by subcpu.py
![screenshot of installing)](https://github.com/MattKemKH/CPE322/blob/main/Lab5/pics/subpubruns.png)
