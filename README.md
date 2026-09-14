# VIPHW1Part2
This the repo for Part 2 of HW 1

Group Members: Will Neubauer, John Devoe, Elchin Hasanov, Raj Mehta, Darshit Shah

This repo contains a branch for each of the three models: FCNN, LSTM, and LSTM with Attention.
Additionally, there is a branch titled VolNorm, which for each of the three models swaps the RevIN for Volitility Normilization. 

Each branch contains a Jupyter notebook to run and a provided csv of the given FRED-MD data. Ensure when running the csv is in the same folder as the notebook. The notebook uses this csv as its data source.

For this assignment we tested five series: RPI, UNRATE, CPIAUCSL, GS5, DPCERA3M086SBEA.
Each of these series is from a different group specific in the FRED-MD working paper. 
This raw data is then transformed using the provided tcodes.

All hyperparameters and seeds were held constant across trials to ensure the only differences in performance we as a results of model architecture.

Our report justifies our model configuration, the results of each forecast, and the implemented extension. 
