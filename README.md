Temporal (wavelet 1D, 2D, sinc 1D, 2D) parameterized filters for EEGNet, SpatialNet, FBCSP, etc. (Comparable networks are provided at the end of the TemporalFilter file and in EEG_ML_WithinSession).

The TemporalFilter class is universal for Wavelet 1D, 2D, Sinc 1D, and 2D, and is parameterized only by the low frequency. Wavelets and Sincs are further parameterized in the subsequent classes, where the temporal parameter is SCALE. The filter functions are placed in the TemporalFilter file.

In EEG_Models files, the models are tested and compared using various methods. This file serves as an example of implementing temporal filters into your workspace.

