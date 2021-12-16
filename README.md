# eecs595-final-project

There are four directories in this project: one directory for the data and three for the models. Git wouldn't let me push these four directories so I had to zip them up individually and upload them manually.

Unzip the four zip files and you should get four directories called "data", "bert", "bi-lstm", and "cnn". Put all of those directories in the same parent directory and the project should be ready to go.

## Data
The data directory contains an .ipynb file that created the combined dataset and saved it to a csv and directories that contain all of necessary data for the models to run. The .ipynb file is self-contained so to run the code, the cells just have to be run. 

## Models
There are three directories for the models: one for Bi-LSTM, one for CNN, and one for BERT.

Each directory has multiple .ipynb files that each contain an experiment conducted for this project.
Each .ipynb file is self-contained so everything that is needed for that experiment is within the file. So to run the code, the cells just have to be run.

The path to the data is hardcoded, so make sure when running these files, the data directory is in the same directory as the model directory.

Note: I conducted all of these experiments in Google Drive and not a local directory so I had to manually change the filepaths to the data and saved models.
