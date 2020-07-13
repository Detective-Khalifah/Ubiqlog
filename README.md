![UbiqLog](https://raw.githubusercontent.com/Rezar/Ubiqlog/ma/app/src/main/res/drawable-hdpi/logo.png)

UbiqLog is a energy-efficient open source tool for "life logging", based on Android platform. It creates a JSON file per day that contains all activities within the device. It is flexible mobile sensing tool, enable users configure its sensors and add/remove new sensors to it.

-	Recent version measures physical activity and location based on Google Play service. However in the source you can change it to the core version, if you are not willing to use Google Play Services. 
-	Visualizations are disabled in this version, because there is work ongoing to make something really different.

Special thanks to Martin Tomitsch, Ping He and Victor Andrei Gugonatu for their design or development support.

####References:
- Rawassizadeh, Reza, Martin Tomitsch, Katarzyna Wac, and A. Min Tjoa. "UbiqLog: a generic mobile phone-based life-log framework." Personal and Ubiquitous Computing 17, no. 4 (2013): 621-637.
- Data Set on Machine Learning Repository
  - Data Set Information:

This is the first smartphone based lifelogging dataset that is going to be available for public use. Please consider that the user of this dataset are obliged NOT to perform any sort of analysis that can harm the privacy of participants. This dataset is not for any privacy related analysis that can re-identify users.
The UbiqLog tool is open source and accessible here: [Web Link]
 - Attribute Information:

With respect to users privacy UbiqLog collects their Calls, SMS headers (no content), App use, WiFi & Bluetooth devices in user's proximity, geographical location (if available and GPS works), physical activities form Google play API.
Data format is in JSON, because there are different sensors and they have different variables. Nevertheless, we have the code for cleaning and converting the data into CSV + smoothing the time. Moreover, we can share our visualization code. Interested individuals could contact the given email address.
