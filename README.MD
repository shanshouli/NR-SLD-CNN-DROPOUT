Description

This work aims to predict Scattering Length Density (SLD) profiles from Neutron Reflectivity (NR) data using a 1D CNN architecture.

Key improvements include:

1. Incorporation of Dropout and SpatialDropout1D layers to mitigate overfitting caused by experimental noise.

2. Removal of the final Sigmoid activation, allowing the model to output unconstrained real values that better reflect the physical characteristics of SLD profiles.


Credits

This project builds on work by:

- Brian Qu ([NR-SLD-CNN](https://github.com/BBQ591/NR-SLD-CNN))  
- Dr. Rajeev Kumar  
- Prof. Miguel Fuentes-Cabrera ([NR-SCFT-ML](https://github.com/miguel-fc/NR-SCFT-ML))
