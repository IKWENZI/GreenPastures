# GreenPastures

Green Pastures is a QlikSense Application to analyse the USDA Dataset to gain insights on USDA Agricultural Data.

Using Interactive Maps, Pie Charts, Time Series Charts and Stack Charts, Green Pastures presents the details on various datasets including Crops, Vegetables, Fruits, Tree Nuts, Dairy & LiveStock.The data is co-related with Precipitation Data and Farmer Market Data is also presented for easy access to the right information.

Through this version, we have created Data Model for the below Entities:

* Production
* Yield
* Sales
* Price Received
* Revenue
* Precipitation
* Area Planted & Harvested
* Pesticide & Manure Use
* Irrigation trends
* Income & Expenses
* Farmer Markets
* Precision Agriculture

But, the scripts are open-source and can be easily extended to add upon further entities and thereby, increase the associative insights that one can obtain.

The data are mainly imported at State level, for monthly or annual values for the past 15 years and can easily be extended to view at County or Agricultural District level.


Green Pastures helps Farmers, Consumers & Researchers in the following way:

1. Using ARMS and NASS datasets, farmers can easily know which are the best crops to grow in their region
2. They can understand the Areas where they can get the maximum yield of a particular crop with the use of best suitable Irrigation technologies
3. Farmers can understand the effect of Rainfall has on the Crop Yield
4. Farmers can compare their yield and other crop Health & Protection information like Height, Moisture, Pesticides & Manure use, with their peers, be it in same region or nationally and take appropriate actions
5. Farmers can understand the adoption of Precision Agriculture in their area and for their Crop
6. Consumers & Farmers, both can get details of nearby Farmer Markets
7. Farmers & Researchers can study the current & Historical trends, and thereby predict future trends

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
