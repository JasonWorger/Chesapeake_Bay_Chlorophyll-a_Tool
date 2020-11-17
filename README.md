**Overview**

Using the Google Earth Engine API and JavaScript coding. A tool was created that allows a user to set a given time and pinpoint a region of interest that using satellite imagery, returns an average chlorophyll-a value. A phytoplankton commonly used to help determine water quality. For this project Chesapeake Bay in USA was chosen as it has a long history of deteriorating water quality and has in-situ measurements that have been used to compare the tools accuracy and reliability to tests its validity for further use.

To produce the following results, it was necessary to analyse the accuracy of the satellite imagery tool. It was coded through Google Earth Engine and allowed for the measurement of chlorophyll-a values within the region of interest at chosen sites. The tool can be assessed through the following link: [https://code.earthengine.google.com/5ea2cc56725bf36721560f4df4391cdd](https://code.earthengine.google.com/5ea2cc56725bf36721560f4df4391cdd)

To interact with the map, click on the inspector tab before clicking on any body of water to determine the chlorophyll-a levels. To change the dates, change the filter dates value and press run to update the satellite imagery.

An example is shown below:

![Example](https://user-images.githubusercontent.com/66956487/99334868-cdde0c00-2878-11eb-87b3-d8991c454f0b.JPG)

**Annual Patterns of Chlorophyll-a**

Collected secondary data and measured MODIS chlorophyll data was used to produce graphs highlighting patterns of chlorophyll-a over a five-year period with each January indicated with a red bar.

![Graphs](https://user-images.githubusercontent.com/66956487/99334847-ccacdf00-2878-11eb-93fc-1507ebaa9455.JPG)

**Spatial Patterns of Chlorophyll-a**

With the use of Google Earth Engine and GIS software a time series analysis of Chesapeake Bay was performed ranging from January 2017 to October 2018 with 4-month intervals. This was to determine whether there are any distinguishable patterns that exist within the Bay over a 21-month period, in particularly whether the maps show a similar increase of chlorophyll-a concentration as the annual pattern&#39;s charts in Figure 6. This particular time period was selected to assess whether the Chesapeake Bay Watershed Agreement has been effective in their goal to reduce water pollution.

![Chlorophyll-a spatial maps](https://user-images.githubusercontent.com/66956487/99334813-c9b1ee80-2878-11eb-9bff-e9b533b95690.JPG)

**Findings**

From the results of the four monitoring stations the overall Pearson&#39;s Correlation Coefficient value R= 0.75 signifies that the MODIS chlorophyll-a tool is an accurate method of calculating chlorophyll-a concentrations. This would confirm that the MODIS tool can be used globally with the assumption that chlorophyll-a phytoplankton is present within that region of interest and with a high level of reliability after the study of multiple sites.

Current monitoring methods of those such as the Chesapeake Bay Program would not be a suitable method when displaying spatial distributions within the bay due to physical restrictions of covering such a vast region within a short period of time. Especially with the fast-changing environments that occur with water pollution processes, emphasizing the need for a more efficient monitoring method that satellite imagery can provide. In-situ measurements only provide values for a point that would support a smaller scope in spatial distributions, the MODIS tool allows for 500 m distributions that current physical collection methods would be unable to produce.

**Author**

Jason Worger
