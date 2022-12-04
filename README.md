# Objective 
The main objectives of WSNs in water quality monitoring systems are to carry real and reliable information from the water environment to remote data monitoring nodes via the LoRa network and end users can access data via mobile phone or personal computer. Identification of suitable algorithms and protocol WSNs for water quality monitoring is a challenge due to the limitation of energy, computation capability, and storage resources of the sensor nodes. We applied ML algorthim to predict the water quality features . 





# Proposed architecture for water quality monitoring framework using WSN and ML  

![image](https://user-images.githubusercontent.com/75506002/205490912-2760d719-af3a-4423-ae14-ce0dc59ee78b.png)


# Dataset 

The data is collected from Lake Tana, which is in the city of Bahir Dar in the north of Ethiopia. This dataset has six separate features, all of which are numerical data  

# Data Pre-processing
- Classify the dataset in to Training and testing with ration 80-20 % 
- Encode the data with onehot encoding for catagorical data and scaling numrical data with min max scaler 


# A model of machine learning that has been employed 

- Autoencoder (AE) 
- Gated Recurrent Units (GRU)
