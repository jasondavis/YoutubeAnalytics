# YouTube Analytics Custom Connector for Power BI
A Microsoft Data Connector or Power Query Connector for YoutubeAnalytics data

The vision:
- A data Connector
- A Power BI Template
- A solution for Youtube Creators

Check on the images of the steps below for a step by step walkthrough on how to get this connector working for you.

**Note** : Unfortunately, Google has implemented some changes to the way that their Web App works and how it handles authentication that have left the documentation on this repo regarding the creation of the WebApp outdated. The Custom Connector still works and does have everything needed to query the data from the REST API, but I'm unable to provide documentation on how to create the Web app. For that, I'd encourage you to follow the tutorials from Google / YouTube themselves regarding the best way to create a web app for their OAuth as mentioned here (https://support.google.com/cloud/answer/6158849?hl=en).

# Step 1: Creating your own Google API project
In order to use this connector, you'll need to create your own Google API Project that will host your specific API credentials. 
Be sure to check out the following video on how to create that project and how to get the credentials needed.  
[![Google API Project](https://i.ytimg.com/vi/6r8hrDHUv6s/mqdefault.jpg)](https://www.youtube.com/watch?v=6r8hrDHUv6s) 

Make sure that the following scopes are enabled on your apps:
- yt-analytics-monetary.readonly 
- yt-analytics.readonly  
- youtube.readonly


# Step 2: Enable the 'Custom Connector' Preview feature in Power BI Desktop
With the new version of the Power BI Desktop you're now able to add a custom data connector way easier than before. With just a few clicks and creating a few folders you're good to go. Be sure to check out the next video on how to enable this feature and set up your folder where you'll place the custom connector.

[![Enabling Power BI Custom Connectors](https://i.ytimg.com/vi/Z_g6ITj2w3w/mqdefault.jpg)](https://www.youtube.com/watch?v=Z_g6ITj2w3w)  

# Step 3: Download and Modify the connector
Once you have the API Project in place and also the Custom Connectors folders, you can now download the *.mez* file and modify it with your Google API Project credentials. This next video will show you how to do that.
[![Installing a Custom Connectors](https://i.ytimg.com/vi/G-NRovNEE0w/mqdefault.jpg)](https://www.youtube.com/watch?v=G-NRovNEE0w)

# Step 4: Get the Power BI Template for this connector
This is a simple report with the Data Model in place, a few measures, all queries set up correctly, and 3 reports to give you a jumpstart to analyze your youtube data. Feel free to modify the report or provide any type of suggestions or modifications to it. This next video will show you how to get started with the Youtube Analytics Power BI Template.
[![Using the Power BI Template](https://i.ytimg.com/vi/WO4dZB3i7fw/mqdefault.jpg)](https://www.youtube.com/watch?v=WO4dZB3i7fw)

# Step 5: Provide Feedback!
Go ahead and test out the connector and the template! If you have any issues with it, please create an issue in this repo or leave a comment in any of the videos of this series. Let me know what you think.

# Update Log
| Date | Description |
| -------- | --- |
| 2019-04-21 | Added a new parameter to the Daily Video Stats and Daily Subscribers functions called "Country Breakdown" which, by default, is set to 'true' for backwards compatibility, but it can be changed to 'false' so these functions only retrieve a daily summary data instead of having a daily breakdown by country for each dataset. |

# Looking for help? 
We offer paid support for anyone looking for help with any Google API application setup or customizations to the Custom Connector.  Contact us at info@poweredsolutions.co for more information.
