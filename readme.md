# Schizophrenia Classification Project
Applied Artificial Intelligence and Robotics Research Lab
Department of Electronic/Electrical Engineering
Obafemi Awolowo University, Ile-Ife, State of Osun, Nigeria.  




## Project Overview
This project aims to provide a high-accuracy classification model that distinguishes Schizophrenia control patients from their healthy counterparts through recorded EEG signals.

## Installation and Setup
### Codes and Resources Used
- Editor Used: Colab Notebook
- Python Version: 3.10.12
### Python Packages Used
- General Purpose: os
- Data Manipulation: pandas, numpy, pyedflib
- Data Visualization: seaborn, matplotlib
- Machine Learning: sklearn, tensorflow, keras

## Data
### Source Data: 
EEG Data Acquisition sessions at the Obafemi Awolowo University Teaching Hospital Complex (OAUTHC)

### Data Acquisition:
EEG data edf files curated by Mr Emmanuel Olateju

## Code Structure
The project is structured in four folders explained as follows:
1. Acquired Dataset: This folder contains the edf files which provide the eeg readings of the patients along with the gnr file for each patient which contain the biodata details of the patient.
2. Data: This folder contains the eeg_data, participants_info and model_data csv files. eeg_data contains the numeric eeg data for all the patients, participants_info contains the biodata of each of the patients, model_data contains the columns of data required for modelling. All the columns in model_data are numeric after necessary conversions.
3. Models: This folder contains the models saved from different trials of training before arriving at the best possible model.
4. Scripts: This folder houses the brainbox of the project. It contains the python scripts used to carry out the data extraction, exploratory data analysis, Machine learning models cross validation and validation, and the final simple neural network model.

## Results and Evaluation:
The metrics used to evaluate the model are accuracy and confusion matrix. The best performing model was got by training simple neural network with a standardized time-series EEG data. The accuracy of this best model is 91.84%. The confusion matrix gives 25 true positive, 20 true negative, 1 false positive and 3 false negative.

## Future Work
Since this model is a simple neural network, more complex neural networks like LSTM, Bi-LSTM, CNN and others can be tested on the data, maybe they can give better accuracies closer to 100%.

## Acknowledgements
I would like to acknowledge and appreciate the mentorship of my Supervisor - Dr K.P. Ayodele -  throughout the course of the project. I would also like to show my heartfelt gratitude to Mr Emmanuel Olateju for providing the dataset and background information about the project. Lastly, I would like to appreciate my colleagues and every other person who contributed toward the completion of this project.

## Disclaimer
This project is a fourth year group design course which forms part of the requirement for attaining the Bachelor of Science degree from the Department of Electrical/Electronics Engineering, Obafemi Awolowo University, Ile-Ife, Osun State, Nigeria.
