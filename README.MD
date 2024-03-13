In this project, Convolutional Neural Networks were used to predict Scattering Length Density curves from Neutron Reflectivity Data.

Using the RDS method, we used Multi_Data_Generation.ipynb to generate 25 different datasets of varying thickness and roughness. Then, 25 CNNs were trained on each dataset using the program called Training_CNNs.ipynb to be saved to a folder. These pre-trained CNN models were then tested on 22 Polyzwitterion Experimental Datasets using the Testing_Models.ipynb code.

With the NRDS method, we used Single_Data_Generation.ipynb to generate one dataset that mimicked the manual fit. The ranges for each parameter were set such that they covered the values of the parameters of the varying temperature and voltage. Then, Single_Train.ipynb was used to train the CNN on the dataset. At the end of this code, you can see the results of the CNN with the experimental data.

RayTune.ipynb was used to find the best set of hyperparameters for the CNNs.