# KNN_Gender_Recognition_by_Voice

Description:
Using Mean frequency & IQR, KNN achieved accuracy of 98/96 for Male/Female prediction, improvement were done using search grid to optimize the K-neighbors count and distance measures. However, no significant improvement were spotted beyond the 98% accuracy.

Confusion Matrix:

![image](https://github.com/Yassir-Mohammed/KNN_Gender_Recognition_by_Voice/assets/103688787/d58758bb-4a31-41f9-a277-3cda87380a0e)


Summary:


![image](https://github.com/Yassir-Mohammed/KNN_Gender_Recognition_by_Voice/assets/103688787/69f96132-805b-4e05-88b9-9f094ee476aa)


dataset source : https://www.kaggle.com/datasets/primaryobjects/voicegender

All Regressors: 
* meanfreq: mean frequency (in kHz)
* sd: standard deviation of frequency
* median: median frequency (in kHz)
* Q25: first quantile (in kHz)
* Q75: third quantile (in kHz)
* IQR: interquantile range (in kHz)
* skew: skewness (see note in specprop description)
* kurt: kurtosis (see note in specprop description)
* sp.ent: spectral entropy
* sfm: spectral flatness
* mode: mode frequency
* centroid: frequency centroid (see specprop)
* peakf: peak frequency (frequency with highest energy)
* meanfun: average of fundamental frequency measured across acoustic signal
* minfun: minimum fundamental frequency measured across acoustic signal
* maxfun: maximum fundamental frequency measured across acoustic signal
* meandom: average of dominant frequency measured across acoustic signal
* mindom: minimum of dominant frequency measured across acoustic signal
* maxdom: maximum of dominant frequency measured across acoustic signal
* dfrange: range of dominant frequency measured across acoustic signal
* modindx: modulation index. Calculated as the accumulated absolute difference between adjacent measurements of fundamental Freq. divided by the frequency range
* label: male or female
