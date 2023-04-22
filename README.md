# PurpleAir-Indoor-and-Outdoor-Air-Quality-Monitors
This is a Crestron example program that shows how data from both PurpleAir PA-II and PA-I-Indoor 
(PurpleAir’s indoor air quality monitor) can be used to automate the process of cooling a home using 
outdoor air in the evening with a whole house fan and motorized windows.  The code allows a user to 
select whether they want the system to:

1.	When the outdoor air quality is poor the smart home will instead cool the home with air conditioning
2.	When the outdoor air quality is poor the home will still use outdoor air to cool the home but 
    will then trigger an indoor air cleaner to remove the pollutants from the air until an indoor air 
    quality monitor says that the air quality in the home is good.

PurpleAir indoor and outdoor air quality monitors are using in this program to monitor the air quality 
inside and outside the home.  

The driver code to communicate with the PurpleAir air quality monitors is written in C# and, without 
too much difficulty, could be ported to another smart home platform.

V2 Has been tested with PurpleAir's latest generation of indoor/outoor air quality monitors
It also combines the basic and detailed modules into a single module
