
# Predicting Data Exfiltration via DNS

## Overview
This repository contains the work on developing machine learning models capable of predicting data exfiltration attempts via DNS queries. It includes both static and dynamic approaches to adapt to various data patterns, ensuring effective detection capabilities in real-time scenarios.

## Contents
- `Static Model .ipynb`: Notebook detailing the development of the static model including data preprocessing, feature engineering, and model training processes.
- `Dynamic Model .ipynb`: Notebook focused on the dynamic model that incorporates real-time data processing and adaptive learning mechanisms.
- `Kafka_dataset.csv`: Dataset intended for the dynamic model, simulating real-time DNS query data through Kafka streams.
- `Static_dataset.csv`: Dataset for the static model training, aimed at analyzing historical DNS query data.
- `Report (2).pdf`: A comprehensive analysis report that outlines the methodologies, analytical processes, and findings of the project.
- `docker-compose.yml`: Docker Compose configuration for setting up the Kafka streaming environment required for the dynamic model's data processing.
- `docker_script.bat`, `docker_script.sh`: Scripts to help set up the Docker environment on Windows and Unix-based systems, respectively.
- `requirements.txt`: Specifies the Python package dependencies necessary to run the project.

## Getting Started

### Prerequisites
- Docker installed on your machine.
- Python 3.x along with Jupyter or any compatible IDE for running the notebooks.

### Setup
1. **Environment Preparation**: Begin by setting up the Kafka environment using Docker. Utilize the provided `docker_script.bat` for Windows or `docker_script.sh` for Unix/Linux systems to automate the setup.
2. **Install Dependencies**: Install the Python dependencies specified in `requirements.txt` by running the following command:
   ```
   pip install -r requirements.txt
   ```
3. **Run the Notebooks**: Navigate to the `.ipynb` notebooks in Jupyter or your preferred IDE. Ensure the Kafka environment is up and running before executing the dynamic model notebook.

## Highlights
- The project showcases a novel approach towards detecting DNS-based data exfiltration attempts using machine learning.
- Detailed data analysis, feature selection, and engineering steps are documented, enhancing the models' predictive accuracy.
- Emphasis on dynamic model development, highlighting its capacity for real-time adaptation and learning from streaming data.

## Additional Information
For a detailed explanation of the methodologies, analysis, and results, please refer to the `Report (2).pdf` included in this repository.

## License
[MIT](https://choosealicense.com/licenses/mit/)

