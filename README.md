# Youtube-Data-Analytics-using-PowerBI ![YouTube](https://cdn.emojidex.com/emoji/xxhdpi/YouTube.png "YouTube")
A minimalistic PowerBI based Dashboard depicting Youtube Data Analytics for your Youtube Channel :smile: 

## Installation:
* The command ***pip install -r requirements.txt** installs the necessary python dependencies for us.
* Ensure you have [***PowerBI Desktop 2020***](https://powerbi.microsoft.com/en-us/downloads/) installed in your system.

## Usage:
* Open your **Google Cloud Console** and navigate to the **APIs and Service** section and select **Library**
* Search for the **YouTube Analytics API** and enable it for your project.
* At the top of the **Credentials page**, select the OAuth consent screen tab. Select an Email address, enter a Product name if not already set, and click the Save button.
* On the **Credentials** page, click the **Create credentials** button and select **Oauth client ID**.
* Select the application type **Other**, enter the name "YouTube Analytics API dashboard using powerbi", and click the **Create** button.
* Click OK to dismiss the resulting dialog.
* Click the **file_download (Download JSON)** button to the right of the client ID.
* Move the downloaded file to your working directory.
* Execute the Python Script: **python main.py** to fetch your youtube analytics data as a Json File. 
    1. *(ensure you update the script with the credentials.json file that you downloaded from the GCP console.)*
    2. *(Source: https://github.com/youtube/api-samples)*
* Proceed with the user authentication and authorization steps, in order to generate the json data dump from Youtube for your channel in the terminal.
* *Ctrl+C* and *Ctrl+V* the json data dump in a blank file and save it as ***data.json*** in the same directory.
* Run the Notebook ***Json_Parsing.ipynb*** which will parse the data from the data dump (json file) to a pandas dataframe and then store it in an Excel Spreadsheet :wink: .
* Launch the PowerBI dashboard and Import the Spreadsheet -> Hit **Refresh** and your dashboard is good to go :heart:

## Dashboard 
<kbd>
<img src="https://user-images.githubusercontent.com/29462447/103466002-d924c280-4d66-11eb-9e85-4cd01f63707f.png" data-canonical-src="https://user-images.githubusercontent.com/29462447/103466002-d924c280-4d66-11eb-9e85-4cd01f63707f.png"/> 
</kbd>

&nbsp;

<iframe width="1140" height="541.25" src="https://app.powerbi.com/reportEmbed?reportId=e267faba-c234-4b8d-af5e-40daa7af7774&autoAuth=true&ctid=d309f125-4bdd-4115-b8ef-f4447333cab7&config=eyJjbHVzdGVyVXJsIjoiaHR0cHM6Ly93YWJpLXNvdXRoLWVhc3QtYXNpYS1yZWRpcmVjdC5hbmFseXNpcy53aW5kb3dzLm5ldC8ifQ%3D%3D" frameborder="0" allowFullScreen="true"></iframe>

###### I made the Youtube Channel just for fun and I am not really active on it, hence the results aren't that pleasing! 😅 
###### Still, it would be awesome if you can check my YouTube Channel here :wink: 👇 and "Subsrcibe":

[![My YouTube Channel Link](https://user-images.githubusercontent.com/29462447/103466326-1cccfb80-4d6a-11eb-9ef1-8ae8447668f2.png)](https://www.youtube.com/channel/UCXJWeuSfr9cNYAK2SX2l8EQ)
