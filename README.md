Temporal (wavelet 1D, 2D, sinc 1D, 2D) parametrized filters for EEGNet, Spatial Net, FBCSP, etc (comparable networks are provided in the end of TemporalFilter File and in EEG_ML_WithinSession).  
class Temporal Filter is universal for Wavelet 1D, 2D, Sinc 1D, 2D, and is parametrized by low freq only. 
Wavelets ans Sincs are parametrized in subsequent classes, where the temporal parameter is SCALE. 
The filter functions are placed in Temporal Filter file.
In EEG_Models files the models are tested and compared through various methods.
This file is an example of implemetning temporal filters into your workspace.
