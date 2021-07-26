# Material Classification from IMU Data

This project was originally assigned as the final group project for *'Intelligent Monitoring of Engineering Systems'* conducted by IAM (Institute for General Mechanics) at RWTH, and was later explored individually from other approaches. 

### Task :  Classify a material given vibration (accelerometer and gyroscope) data

- **Approach 1** : (Machine Learning Approach) define features like mean, rms value, amplitude etc. manually on the sampled time-domain signal and feed a fixed batch of samples to the Classification Learner.
- **Approach 2** : (Deep Learning Approach)  transform the signal into a wavelet or a power-spectrogram and feed it to the SOTA-CNN architecture.
