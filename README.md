# Video Surveillance Anomaly Detection

## Description
This project is designed for video surveillance and anomaly detection. It uses the Avenue dataset to train a model on normal (non-anomalous) data. When running, the system checks the root mean squared error (RMSE) between the trained model and the input video file to determine if there is any anomaly.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Anomaly Detection](#anomaly-detection)
- [Contributing](#contributing)

## Installation
1. Clone the repository

2. Navigate to the project directory

3. Install the required dependencies


## Usage
To run the anomaly detection, use the Video_Surveillance.ipynb file

## Dataset 
The project uses the Avenue dataset for training. The dataset contains videos of normal activities without any anomalies. 

## Anomaly Detection
The anomaly detection process involves calculating the root mean squared error (RMSE) between the trained model and the input video file. If the RMSE exceeds a certain threshold, the system flags the video as containing an anomaly.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes. Make sure to follow the coding standards and include tests for any new features.
