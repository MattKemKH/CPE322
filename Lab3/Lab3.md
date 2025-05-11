## Matthew Kemenosh
## Lab 3 - Python
### Installing Python Packages
![screenshot of installing)](installpy.png)
### cd~/iot  |  cd *3
changes directory to iot from previous labs GitHub repository copied. Then changes into lesson 3 directory.
![screenshot of cd)](cd~_3.png)
### julian.py | date_example.py | datetime_example.py
python julian.py runs a python script called julian.py. It gives the calendar date, Julian date, and modified Julian date. python date_example.py runs a python script called date_example.py. It gets the current date, formats it in a couple different ways, and calculates the number of days since the first day of classes and until the last day of classes. python datetime_example.py runs a python script called datetime_example.py. It displays time in a couple different ways using the datetime and time modules.
![screenshot of 1st 3 py commands)](judt_dt.png)
### time_example.py | sun.py "New York" | moon.py
python time_example.py runs a python script called time_example.py. It continuously prints the current local time every 10 seconds until interrupted. You can stop this by pressing Ctrl C. python sun.py "New York"  runs a python script called sun.py. It takes in a city, then gives data regarding the sun such as sunrise, sunset, dawn, dusk, and noon. python moon.py runs a python script called moon.py. It prints out the phases of the moon for the next 30 days starting with the current day.
![screenshot of 2nd 3 py)](timesunmoon.png)
### coordinates.py "Samuel C. Williams Library" | address.py "40.74480675, -74.02532861159351" | cpu.py
python coordinates.py runs a python script called coordinates.py. It takes in an address or landmark, uses the geopy library to find its geographical coordinates, and prints the full address along with its latitude and longitude. python address.py runs a python script called address.py. It takes in geographical coordinates, uses the geopy library to find the corresponding address, and prints the full address along with its latitude and longitude. python cpu.py runs a python script called cpu.py. It displays the number of physical and logical CPU cores and prints CPU utilization percentages for each core every second for 10 seconds.
![screenshot of 3rd 3 py)](coordadcpu.png)
### battery.py | documentstats.py document.txt
python battery.py runs a python script called battery.py. It prints current battery statistics (percentage, seconds left, and whether or not computer is plugged in). python documentstats.py runs a python script called documentstats.py. It reads a text file (in this case document.txt), counts the occurrences of wordsmexcluding common stop words, and prints the total word count along with the top ten most frequent words.
![screenshot of last 2 py)](battdoc.png)

