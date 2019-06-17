# Demand Prediction

## Background
I made this project as a submission to Grab's <a href = "https://www.aiforsea.com/challenges">AI for S.E.A.</a> challenge. The project consists of future demand prediction given a few features across 61 days.

The easiest way to run this project is through the attached Jupyter notebooks

### Dataset
The main dataset used in this project is the training set given by Grab. It contains >6m rows of demand data over 60 sequential days. 

### Preprocessing
Prior to training, several preprocessing steps were performed.  Firstly, I removed outlier timestamps with no data, then one-hot encoded the dataset with geohashes as index and each timestamp as a feature. The dataset was then split into training, validation and testing sets through the sliding window method. 


## Testing

To test the model, please perform the following steps.

1. Clone this repository into a folder in your machine
```
git clone https://github.com/Te000/GrabChallenge.git
```
2. Create a virtual environment and install the dependencies within the virtual environment
```
conda create -n grabChallenge python=3.6
conda activate grabChallenge
pip install -r requirements.txt
```
3. Run Jupyter Notebook by running the following command inside the repository
```
Jupyter notebook
```

4. Open the file: Prediction_Script.ipynb

5. Follow the instructions in the Notebook to proceed! Happy Testing!
# GrabChallenge
