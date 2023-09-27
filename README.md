# Change-Detection-using-ArcGis
If you would like to perform change detection and time series analysis in ArcGIS, this tool would be helpful

To run this model, the user only needs six different time series of NDVI raster files, an output directory, and a polygon layer representing plot boundaries. The plot boundary layer should contain a column named "Plot_ID" that provides unique IDs for each plot.

![image](https://github.com/AliBgisrs/Change-Detection-using-ArcGis/assets/109620013/74378730-8284-43f5-9297-ebf403224daa)

 Please make sure that you have already installed python and matplotlib library before running the tool. 
 
After running the model, it will create five subfolders (Calculations, Classified_NDVI, Anomaly_Detection, Excel, and Time_series_plots) along with a geodatabase (gdb.gdb) within the specified output directory. 

![image](https://github.com/AliBgisrs/Change-Detection-using-ArcGis/assets/109620013/909a8d1b-32ce-45c7-b732-090d91ff8194)

The contents of each subfolder are as follows:
Calculations: This folder contains the calculated layers generated during the model's operation. You can safely remove this folder once the model operation is completed.

Classified_NDVI: In this folder, NDVI is classified for each time point, and it displays a heatmap of the classification results. 

 ![image](https://github.com/AliBgisrs/Change-Detection-using-ArcGis/assets/109620013/22385f58-d744-4c5f-8ed6-c9873b07ca9d)

![image](https://github.com/AliBgisrs/Change-Detection-using-ArcGis/assets/109620013/9ef1a48e-12ec-4d29-b718-81b394ac5e7a)


Anomaly_Detection: This folder contains classified heatmaps that highlight anomalies for each pair of time periods in the time series. The anomalies are categorized into different classes, such as "Increased," "No significant changes," and "Decreased." 
 
![image](https://github.com/AliBgisrs/Change-Detection-using-ArcGis/assets/109620013/cb5b4a9e-1d72-4f08-972e-ab02f8fea413)

![image](https://github.com/AliBgisrs/Change-Detection-using-ArcGis/assets/109620013/56c26f04-1904-4c77-80d1-59a2ef801e4c)

Excel: This folder stores Excel files that contain the time series of NDVI changes for each plot.


 ![image](https://github.com/AliBgisrs/Change-Detection-using-ArcGis/assets/109620013/536b5379-ecbd-4f37-aea5-4336ca034441)

Time_series_plots: This folder contains line graphs illustrating the time series of the mean NDVI values over the specified time period.
 
![image](https://github.com/AliBgisrs/Change-Detection-using-ArcGis/assets/109620013/03be6f4e-8016-421d-9dd5-fa34f1c4cbac)

 
![image](https://github.com/AliBgisrs/Change-Detection-using-ArcGis/assets/109620013/db7df01d-1be1-4e24-ac5f-353e8960d14e)


