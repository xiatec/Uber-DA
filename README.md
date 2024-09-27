# Uber Data Analytics | Modern Data Engineering GCP Project

## Introduction

This project aims to perform data analytics on Uber data using various tools and technologies, including Google Cloud Platform (GCP) Storage, Python, Compute Instance, Mage Data Pipeline Tool, BigQuery, and Looker Studio. The project provides insights into taxi trip records, enabling users to analyze patterns and trends in transportation data.

## Architecture 
![Architecture](architecture.jpg)

## Technology Used
- **Programming Language**: Python
- **Google Cloud Platform**:
  - Google Storage
  - Compute Instance 
  - BigQuery
  - Looker Studio
- **Data Pipeline Tool**: [Mage](https://www.mage.ai/)

## Dataset Used
The dataset used in this project is the TLC Trip Record Data, which includes yellow and green taxi trip records. The dataset captures various fields such as pick-up and drop-off dates/times, locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts.

You can access the dataset used in the project [here](https://github.com/darshilparmar/uber-etl-pipeline-data-engineering-project/blob/main/data/uber_data.csv).

For more information about the dataset, visit:
1. [NYC TLC Trip Record Data](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)
2. [Data Dictionary](https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf)

## Data Model
![Data Model](data_model.jpeg)

## How to Run the Project

1. **Install Dependencies**: Ensure you have Python and pip installed. Use the following commands to install the required packages:
   ```bash
   sudo apt-get update
   sudo apt-get install python3-distutils
   sudo apt-get install python3-apt
   sudo apt-get install wget
   wget https://bootstrap.pypa.io/get-pip.py
   sudo python3 get-pip.py
   sudo pip3 install mage-ai pandas google-cloud google-cloud-bigquery
   ```

2. **Clone the Repository**: Clone the project repository from GitHub.
   ```bash
   git clone https://github.com/mage-ai/mage-ai
   cd mage-ai
   ```

3. **Run the Jupyter Notebook**: Launch Jupyter Notebook to execute the data pipeline.
   ```bash
   jupyter notebook
   ```

4. **Execute the Pipeline**: Open the `Uber Data Pipeline (Fixed Version).ipynb` notebook and run the cells sequentially to load, transform, and analyze the Uber data.
