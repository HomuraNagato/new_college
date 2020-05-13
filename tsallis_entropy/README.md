
# Tsallis-entropy for dropped packets

This project aims to uncover anomalies on dropped packets at a firewall using a large
network provider data. Most code has been lost, however a presentation on tsallis entropy
is still available as well as an image of an avenue of research. 

The photo normal_model_predictions.png shows a month of firewall data (source code unfortunately lost). 
Tsallis-entropy with a q-value of 2 was calculated on the data. This was then differenced and plotted 
on the yellow line. Anomalies represented by red dots were plotted. An ARMA model was evaluated 
that reduced spurious outliers to capture events that had a highly likely probability of being
an anomalous event.
