# QuantiPy

<strong>"What gets measured gets managed"</strong> - <em>Peter Drucker</em>

Quantify your daily antics in which you are on and/or carrying a computer. The idea of this project is to create an AIO self hosted event log that is able to bring data together automagically to create an automated log of what happened on a given day. 

The goal of this project is to be FOSS with integration with tools that are available to give a dashboard view or a skeleton of a journal that doesn't require interaction.

This project may function as a bit of a "choose your own adventure game" in that it will offer a starting ground of a dashboard. As a user of the tools listed below the output can be customized on an opt-in basis.

https://add1son.com/blog/quantipy/

## What do we want to collect for self analysis?
* Heath Data - Heart Rate, Steps, Sleep, Meditation, Weight
* Intake - Food / Calories
* Location - Where you were out and about during the day 
* Computer / Phone Use - Can be as abstract as screentime or in depth as application based use 

--------------------
  - [Data Sources](#datasources)
  - [Data Display](#datadisplay)
-----------------------------------------------------------------------------

## Data Sources
 * [OpenStreetMap](https://www.openstreetmap.org) - Google Maps Replacement with API access
 * [GPSLogger by Basic Air Data](https://github.com/BasicAirData/GPSLogger) - GPS Logger for Android (Replacement for Google Location History)
 * [GPSLogger by mendhak @ gpslogger.app](https://github.com/mendhak/gpslogger) - GPS Logger For Android (Battery efficient Google Location History Replacement)
 * [Wger](https://wger.de/en/dashboard) - Workout Manager, Manages exercises and personal workouts, weight and diet plans with REST API access ([Source Code](https://github.com/wger-project/wger))
 * [OpenBand](https://github.com/UgoRaffaele/xiaomi-miband-android) - Xiaomi Mi Band integration software for Android, 3 years old but may still work for this project ([Source Code](https://github.com/UgoRaffaele/xiaomi-miband-android))
 * [mitmproxy](https://blog.heckel.xyz/2013/07/01/how-to-use-mitmproxy-to-read-and-modify-https-traffic-of-your-phone/) - Obstructive but very thorough method of catching all traffic allowing for analysis of data
 * [Garmin Connect](https://connect.garmin.com/) - Garmin wearable data source. Exports heart rate, sleep, steps and stress via proprietary .fit file format or CSV 
 * [Cronometer](https://cronometer.com) - Calorie Tracking / Weight Tracking / Garmin data import. Also integrates with additional fitness trackers like Fitbit.
 * [Reverse Engineered Whatpulse](https://github.com/sim642/whatpulse) - Whatpulse has no real alternatives so someone reverse engineered the source code. [Whatpulse](https://whatpulse.org) is a great application which collects all kinds of data on how you use your computer but it is sent to a 3rd party.
## Data Display
 * [umap](https://umap.openstreetmap.fr/en/) - Create layers on OpenStreetMap and Embed and share your map ([Source Code](https://github.com/umap-project/umap))
 * [RedNotebook](https://rednotebook.sourceforge.io/) - GPL licensed Journal that allows for a lot of really useful features. 
## Resources & Comparisons 
* [OpenStreetMap Android App Comparison](https://wiki.openstreetmap.org/wiki/Comparison_of_Android_applications)
