# Short-Term Traffic Forecast Project

## Introduction
This project aims to develop a short-term traffic forecasting system using Java. The project utilizes a layered autoencoder design for predicting traffic situations, improving traffic flow prediction accuracy. It can also run in a Big Data environment using Hadoop.

## Prerequisites
- NetBeans IDE
- Java Development Kit (JDK)
- Traffic dataset in text format
- Google Maps API key (for visualization)
- VMware with Linux OS (for Hadoop mode)

## How to Run the Project

### 1. Open NetBeans IDE
**Open Project in NetBeans IDE**

**Description:**
The project coded in Java language is opened in NetBeans Integrated Development Environment.

### 2. Run the Project
**Run Project**

**Description:**
The project opened in NetBeans IDE is run by clicking the green play button on the menu bar.

### 3. Load Traffic Dataset
**Load Traffic Dataset**

**Description:**
Once the project starts execution, the GUI opens. Browse and load the text file that contains the required traffic dataset to train the model.

### 4. Train the Model
**Train the Model**

**Description:**
After browsing and uploading the traffic dataset, enter the required K-value and click the train button to start training.

### 5. Display Spatial Correlation Values
**Spatial Correlation Values**

**Description:**
Once the training is complete, the spatial correlation values for each location are displayed in the Log.

### 6. Load Forecast Locations
**Load Forecast Locations**

**Description:**
Browse and upload the text file containing the locations for which the traffic congestion should be forecasted.

### 7. Forecast
**Forecast**

**Description:**
Enter the Date and Time interval and click the Forecast button to begin forecasting.

### 8. Output on Google Maps API
**Predicted Values on Google Maps API**

**Description:**
The predicted traffic congestion values are displayed on the Google Maps API. Roads marked in red indicate high traffic congestion. Roads marked in green indicate low traffic congestion.

### 9. Performance Graph
**Performance Graph**

**Description:**
Click on the performance tab to view the graph. The forecasted values using KNN and ARIMA are compared with real values. From this, we can see that the values predicted by KNN are very close to the actual values.

## Running in Hadoop Using Linux OS in VMware

### 10. Run NetBeans in Linux
**NetBeans in Linux**

**Description:**
The project coded in Java language is opened in NetBeans IDE in Linux.

### 11. Running in Big Data Mode
**Forecast in Big Data Mode**

**Description:**
After training the model with the required traffic dataset, upload the necessary forecast location, enter the day and time interval. Click “Forecast in Big Mode” to run the project in Hadoop.

### 12. Output in Log
**Result in Big Data Mode**

![Result](https://github.com/srijaaaaa/Traffic-Forecasting-System/blob/main/Output/result.jpg)


**Description:**
The predicted traffic congestion values in the given forecast locations are processed in Hadoop and displayed in the Log.

## Conclusion
This project provides an efficient solution for short-term traffic forecasting using Java and can scale to handle Big Data using Hadoop. By following the steps outlined above, users can load datasets, train models, and forecast traffic conditions accurately.
