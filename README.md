# GreenPastures

Green Pastures is a QlikSense Application to analyse the USDA Dataset to gain insights on 

To Install the Application:
1. Please install Free Data Visualization Tool - Qlik Sense Desktop from http://www.qlik.com/try-or-buy/download-qlik-sense after registration 
2. Copy the uploaded file "Green Pastures.qvf" to the QlikSense Home directory, typically, C:\Users\<youruser>\Documents\Qlik\Sense\Apps\
3. Open Qlik Sense Desktop. Go to Desktop Hub. Green Pastures will be available. Click on it. After that, explore the App! Sample Steps are provided in the Video: https://www.youtube.com/watch?v=A6lGDl3NjAU

In order to update data, open the Data Load Editor and edit the below Libraries, which are mapped in the Data Folder in the GIT:
1. Big Data (stores the KML for states)
2. NASS (For NASS Data)
3. ARMSDB (For ARMSDB Master Data, Mapping for Commodities with NASS and Precipitation Data)
4. ARMSDB/SURVEY (For Arms Survey Data)

As and when new data is made available for NASS & ARMSDB, keep them in NASS and ARMSDB/Survey Folder and re-run the Load Scripts. Data will be imported and available in Dashboards.
