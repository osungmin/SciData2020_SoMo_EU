# SciData2022_SoMo_EU


Paper codes for "High-resolution European daily soil moisture derived with machine learning (2003-2020)", submitted. 

SoMo.ml-EU provides European daily soil moisture data at daily and 0.1 degree scales. The data is generated using a machine-learning based model trained with in-situ soil moisutre measurements from ISMN networks over Europe and the US (https://ismn.geo.tuwien.ac.at/en/).

Long Short-Term Memory based model to generate SoMo.ml-EU: /lstm_model
Conda environment can be created from somo_lstm.yml

$ conda env create -f somo_lstm.yml
