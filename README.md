# Sign Language Detection

This project focuses on detecting American Sign Language (ASL) gestures using machine learning. The aim is to create a model that can recognize and classify different ASL signs, facilitating communication for the deaf and hard of hearing.

## Project Overview

- **Data Collection**: Collected gesture data using a webcam.
- **Data Processing**: Preprocessed images and created datasets for training.
- **Model Training**: Used a Convolutional Neural Network (CNN) for classification.
- **Testing**: Evaluated model performance and accuracy.

## Files

- `collecting_data.py`: Script for collecting gesture data.
- `processing_data.py`: Data preprocessing script.
- `model_train.py`: Script to train the CNN model.
- `model_test.py`: Script to test the model.

## Requirements

- Python 3.x
- OpenCV
- TensorFlow
- Numpy

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/pritesh-sh21/MIniProject2.git

2. Navigate to the project directory:
    ```bash
   cd SignLanguage_AMSS

3. Install the required libraries:
   ```bash
   pip install -r requirements.txt

## How to Run
1. Run the data collection script:
   ```bash
   python collecting_data.py
2. Train the model:
    ```bash
    python model_train.py
3. Test the model:
   ```bash
   python model_test.py

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License.
This version includes all instructions and formatting properly laid out for your README file.
