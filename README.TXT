# Short term power availability forecast
Repository containing the code for :
"Short term power availability forecast for EV charging hubs using Machine Learning techniques" 
(Master Thesis in Electrical and Computer Engineering - Técnico Lisboa). 

# Author:
Tomás Maria Reis Bogalho - tomas.bogalho@tecnico.ulisboa.pt

# Abstract:
The Energias de Portugal (EDP) building located in Lisbon, Portugal is equipped with a Photovoltaic (PV) system responsible for generating 70 kWp (kilowatt ”peak”). In addition, it comprises an Electric Vehicle Central Charging System (EVCS), capable of adjusting the power used according to the overall available power in the building. Although the EVCS has access to the current available power in thebuilding, it would be possible to optimize its operation by also providing it with forecasts of the available power in the building in the near future, for example, with values for 5, 10 and 15 minutes from now. To meet this requirement, we have introduced a system consisting of Machine Learning (ML) techniques. Several factors, both meteorological as well as energetic, have been used to predict the future available power. The implementation was accomplished using three different architectures, Vanilla Recurrent Neural Network (RNN), Encoder-Decoder and One Dimensional Convolutional Neural Network (1D CNN)-Encoder-Decoder. For each of the three architectures, two types of RNNs were tested, Gated RecurrentUnit (GRU) and Long Short-Term Memory (LSTM), thus resulting in a total of 6 different models: Vanilla GRU, Vanilla LSTM, GRU-Encoder-Decoder, LSTM-Encoder-Decoder, 1D CNN-GRU-Encoder-Decoder and 1D CNN-LSTM-Encoder-Decoder. It was also attempted to introduce Monte Carlo Dropout (MCD) to the proposed architectures, allowing a probabilistic interpretation of the results obtained, and  thecomputation of confidence intervals of the forecasts carried out.
