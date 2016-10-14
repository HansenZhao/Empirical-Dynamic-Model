# Empirical-Dynamic-Model

Test for Empirical Dynamic Model in Matlab Code

Identify Causality between two variable observed in time series

To Test the algorithem, For example: we observed the intensity of fluorescence of GFP X and the intensity of fluorescence of RFP Y in single cell from time = 0s to time = 100s in step of 1s;

raw data can be transform to dataSet with 101rows and 2 column

edm = EDM(dataSet);
result = edm.estimateFromTo(indexRes,indexTar,e,tau);//estimate from variable in column[indexRes] to variable in colum[indexTar] by space                                                      //dimension of [e] and time delay of [tau], return set in two column 
                                                     //column(1) is the real target value, column(2) is eatimated value

# Paper

Sugihara, G., May, R., Ye, H., et al. 2012. Detecting causality in complex ecosystems. Science (New York, N.Y.) 338, 6106, 496–500.
