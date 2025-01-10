# Sign Language Detection using LSTM

This project implements a sign language detection system using Long Short-Term Memory (LSTM) neural networks. It leverages **Mediapipe**, **TensorFlow**, and other powerful libraries to capture, process, and classify hand gestures into respective sign language labels.

## Features
- **Dynamic Hand Gesture Recognition:** Recognizes hand movements using video input.
- **Customizable Training Data:** Users can capture their own data to train the model, ensuring adaptability to various sign languages or personal styles.
- **Easy-to-Use Framework:** Modular code to make it beginner-friendly and extendable.

## Libraries Used
The following libraries are required to run this project:
- **[mediapipe](https://google.github.io/mediapipe/):** For hand landmark detection.
- **[tensorflow](https://www.tensorflow.org/):** For building and training the LSTM model.
- **[matplotlib](https://matplotlib.org/):** For visualizing data and results.
- **[opencv-python](https://pypi.org/project/opencv-python/):** For video processing and frame capture.
- **[scikit-learn](https://scikit-learn.org/):** For preprocessing and evaluating the model.
- **[numpy](https://numpy.org/):** For numerical operations.
- **cv2 (from OpenCV):** For video and image handling.

## How It Works
1. **Data Capture:** Users can capture their own training data using the provided script. The captured data is stored in a format suitable for model training.
2. **Model Training:** The LSTM model is trained on the user-provided data. The training process is easy to initiate and customizable.
3. **Real-Time Prediction:** Once trained, the model can be used for real-time sign language detection through a live video feed.

## Getting Started

### Prerequisites
Ensure you have Python installed on your system. This project supports Python 3.7 and above.

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/sign-language-detection.git
   cd sign-language-detection
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```


## Customization
This project allows you to:
- Add new gestures or signs by capturing and labeling new data.
- Modify the LSTM architecture to experiment with different configurations.
- Extend the model for other applications beyond sign language detection.

## Contributions
Contributions are welcome! Feel free to fork this repository and submit a pull request.


## Acknowledgments
- Mediapipe for their outstanding hand tracking solution.
- TensorFlow and the open-source community for providing robust tools for deep learning.
- And also thanks to nicknochnack.

This project was done in 2023 and some functions might not work as expected.

Happy Coding! 🎉

