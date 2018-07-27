This repository is a part of the implementation in project iRoads - smartphone-based road condition monitoring solution. In iRoads we have to detect and classify road anomaly (potholes, bumps) data based on smartphone acceleration data and vehicle speed data using machine learning techniques. This anomaly identification can be done through a threshold based approach  or a machine learning approach. In this solution we have currently used a classification process to identify road anomalies. 

Datasets were created by our own. When creating the the training dataset road anomalies were tagged manually as
      potholes: ‘P’,
      bumps: ‘B’ and 
      other data points(normal): ‘N’

Features we used to detect anomalies were 3-axis acceleration vector readings from accelerometer sensor of smartphones and vehicle speed. 

To run this notebook
  1. clone the repository and cd into the directory
  2. run "jupyter notebook"
  3. select "AnomalyDetector.ipynb" from opened web page in browser
