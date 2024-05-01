# Heart Beat Sound Modeling 
- This project is models heart beat sounds , to generate insights about the health of the patient . 
- It expects a `audio_files` directory in the root directory which contains the heart beet sounds .
- Create the virtual environment and run `pip install requirements.txt` to install the dependencies 

## Execution Order 
- Run `l1_preprocessing.ipynb` which uses the `Heartbeat_Cusat - Form responses 1.csv` file and the file names in `audio_files` to generate `output.csv` which map the individual's data with corresponding file paths
- Run `l2_preprocessing.ipynb` which uses the `output.csv` to have a level - 2 preprocessing to split the audio files and to generate the required folders and csv files for modeling 
- Run `random_forest.ipynb` to train and generate the model file
- You can use `test_model.ipynb` to check the predictions 