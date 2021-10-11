# kmlFileGenerator

# Steps:

Retrieve GPRMC (GPS NMEA0183 coordinates) data from UDP \\
Decode the GPRMC Data (Latitude, Longitude, Date, Time)
Create a donut from the GPS coordinate as its centre 
The inner circle of the donut is used to pinpoint the boat's location
The outer circle is retrieved from the user input
Generate a kml file with the donut list of coordinates (We actually create a polygon with 36 data points)
Use Selenium to open the Windy Uploader Webpage 
Automatically import the generated kml file 

# User Inputs 

Radius of outer donut 
Colour of the donut's core 
Automatic or Manual Refresh 

# The .py files

main.py is the file you run 
functions.py is the file where we store all the functions 

# ChromeDriver.exe

Make sure you download the appropriate ChromeDriver depending on your Chrome Version
The website to download ChromeDriver is : https://chromedriver.chromium.org/downloads
Put the ChromeDriver in the following directory :
C:\\Windows\chromedriver.exe

# Packages Used 

selenium
math 
simplekml
time
datetime
socket 
os 
