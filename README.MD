In this project, Convolutional Neural Networks were used to predict Scattering Length Density curves from Neutron Reflectivity Data.

When attempting to generate good results for the experimental NR curves blindly (or without knowing the parameters), we used the Multi_Data_Generation.ipynb to generate 25 different datasets of varying thickness and roughness. Then, 25 CNNs were trained on each dataset using the program called Training_CNNs.ipynb. The results were tested in the file called Testing_Models.ipynb.

To generate the results once we had the parameters from the manual fits, we used Single_Data_Generation.ipynb to generate one dataset that mimicked the manual fit. Then, Single_Train.ipynb was used to train the CNN on the dataset. At the end of this code, you can see the results of the CNN with the experimental data.

RayTune.ipynb was used to find the best set of hyperparameters for the CNNs.