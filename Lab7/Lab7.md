## Matthew Kemenosh
## Lab 7 -  ThingSpeak and Google Sheets
## ThingSpeak
### Sign up and log in MathWorks ThingSpeak
I first signed up and logged into MathWorks ThingSpeak. I created a  new channel named cpu_loop with field1 cpu_pc and field2 mem_avail_mb, and copied my Write API key.
### Installing psutil
Then I installed psutil and copied thingspeak_cpu_loop.py and thingspeak_feed.py to my working directory demo.
![screenshot of installing)](https://github.com/MattKemKH/CPE322/blob/main/Lab7/pics/instalcps.png)
### Run thingspeak_cpu_loop.py or thinkspeak_feed.py in a demo folder
I utilized cat to view both of the python scripts
![screenshot of installing)](https://github.com/MattKemKH/CPE322/blob/main/Lab7/pics/cats.png)

Then after running thingspeak_feed.py I was prompted to enter my ThingSpeak API key, which I then entered.
![screenshot of installing)](https://github.com/MattKemKH/CPE322/blob/main/Lab7/pics/tsfeed.png)

After this I was able to visit the ThingSpeak website and view my CPU usage and available memory
![screenshot of installing)](https://github.com/MattKemKH/CPE322/blob/main/Lab7/pics/cpus.png)
## Google Sheets
### Log in the Google Cloud Platform Identity and Access Management, create a project cpudata, enable both Drive API and Sheets API, create and download service account JSON key file
First I set up my Google Cloud Platform Identity and Access Management. Then I created an a project named cpudata, enabled the Drive API and Sheets API, created a JSON key, and downloaded it.
### Install gspread and oauth2client
After getting my JSON key I downloaded the necessary python libraries and copied the .py files into my directory.
![screenshot of installing)](https://github.com/MattKemKH/CPE322/blob/main/Lab7/pics/gspreadinst.png)

### Run cpu_spreadsheet.py with the JSON key file in a demo folder
I copied cpu_spreadsheet.py to my directory since I was running it on my comptuer and not a Raspberry Pi.
![screenshot of installing)](https://github.com/MattKemKH/CPE322/blob/main/Lab7/pics/jsoncp.png)

In Google Sheets I started a new spreadsheet cpudata and shared it with the client_email address inside of my JSON file. I deleted rows 2 to 1000, and edited the header cells. After using nano to write my json key inside cpu_spreadsheet.py, I ran the Python script.
![screenshot of installing)](https://github.com/MattKemKH/CPE322/blob/main/Lab7/pics/cpurun.png)
![screenshot of installing)](https://github.com/MattKemKH/CPE322/blob/main/Lab7/pics/sheets.png)
