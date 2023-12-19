1.)Human Activity Recognition Dataset by UCL is utilized.
2.)Utilized KNN for classifying 19 different activities on the basis of sensor data.
3.)Achieved an accuracy of 65% and accuracy of 97% using CNN.
4.) Data interpolation and features like mean, standard deviation, skew and kurtosis utilized.
Some Observations :-)

1.)An interesting insight was to first denoise the data and then start with feature extraction
Here's an image for the denoised and original data (Here Savgol Filter is used)
![image](https://github.com/AMNS4000/Human-Activity-Recognition-UCL-Dataset-using-KNN/assets/104384727/9e0a85ae-864a-456f-a1ce-bda91f189fe0)

2.) Data interpolation provided some significant observations like the pattern of readings is almost similar for a period of 25 seconds. Hence we break the data into sets of 125 columns to increase the
robustness of the model
![image](https://github.com/AMNS4000/Human-Activity-Recognition-UCL-Dataset-using-KNN/assets/104384727/25c78474-052e-49be-8689-6daa89155ce5)




