
# Human Activity Recognition

This project uses accelerometer and gyroscope data from smartphones to classify human activities, such as walking, sitting, standing, and lying down. The dataset includes recordings from 30 subjects performing these activities while carrying a smartphone on their waists.

## Dataset
- **Source**: UCI HAR dataset
- **Activities**: Walking, Walking Upstairs, Walking Downstairs, Sitting, Standing, Laying
- **Sensors**: Accelerometer and Gyroscope (capturing 3-axial signals in X, Y, and Z directions)

## Features
- 561 features derived from the time and frequency domain, including signals such as body acceleration, body gyroscope, and their respective jerks.
- Fourier transforms and other feature engineering techniques applied to extract useful information from sensor data.

## Models Implemented
1. **LSTM**: Used for sequence modeling to capture time-dependent patterns in sensor data.
2. **CNN**: Applied to recognize activity patterns from filtered sensor signals.
3. **Divide and Conquer Strategy**: Classified activities into dynamic and static, then further refined classification within each group.

## Key Results
- **Accuracy**: Achieved up to 96% accuracy using the divide and conquer approach with CNN and LSTM layers.
- **Improvement**: The divide-and-conquer strategy helped enhance model performance from 90% to 95.6% accuracy.

## Conclusion
The combination of LSTM and CNN models, along with feature engineering and a divide-and-conquer classification strategy, provided highly accurate activity recognition.
