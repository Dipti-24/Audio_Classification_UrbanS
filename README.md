# Audio Classification using the Sound8K Dataset

## Project Overview

This project focuses on audio classification using the Sound8K dataset. The goal is to classify audio clips based on their content by extracting meaningful features from the raw audio data and feeding them into a machine learning classifier.

## Dataset

The dataset used in this project is the Sound8K dataset, which contains various labeled audio clips representing different sound categories.

## Features Extraction

To process the raw audio data, we extract MFCC (Mel-Frequency Cepstral Coefficients) features using the librosa library. The extracted features serve as inputs to the machine learning model.

## Tech Stack
1. Python
2. Librosa
3. Matplotlib
4. Pandas
5. NumPy
6. TensorFlow
7. Keras
8. Resampy
9. MFCCs
## Requirements

Ensure you have the following dependencies installed:

pip install librosa tensorflow numpy scikit-learn resampy

## Implementation Steps

**1. Load the dataset:** Extract and organize the audio clips with their respective labels.

**2. Feature Extraction:** Convert raw audio into MFCC features using librosa.

**3. Preprocessing:** Normalize and reshape the extracted features.

**4. Model Training:** Train a deep learning model (e.g., CNN, LSTM, or MLP) on the extracted features.

**5. Evaluation:** Assess model performance using accuracy, precision, recall, and F1-score.

**6. Predictions:** Use the trained model to classify new audio samples.

## Conclusion

This project successfully classifies audio clips using MFCC feature extraction and deep learning techniques. Further improvements can be made by experimenting with different neural network architectures and feature extraction technique.

## License

This project is licensed under the [MIT License](https://github.com/Dipti-24/Audio_Classification_UrbanS/blob/main/LICENSE).

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to enhance functionality.

## Contact
For any queries or collaboration opportunities, feel free to reach out:

 **Email:** mishradipti2402@gmail.com



