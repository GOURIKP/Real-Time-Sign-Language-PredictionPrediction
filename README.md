# Real-Time Sign Language Prediction

## Overview
This project aims to predict American Sign Language (ASL) gestures for alphabets A-Z in real-time using a webcam. It leverages a pre-trained VGG16 model for image classification and integrates with a user-friendly interface built with Streamlit.

## Features
- **Real-time prediction of ASL gestures (A-Z)**
- **Webcam integration for capturing gestures**
- **User-friendly interface built with Streamlit**
- **High accuracy of 0.99**

## Dataset
The project uses the ASL Alphabet Dataset from Kaggle:
[ASL Alphabet Dataset](https://www.kaggle.com/datasets/grassknoted/asl-alphabet)

## Tools and Technologies
- **Python**: Programming language used for the project.
- **TensorFlow and Keras**: For building and training the VGG16 model.
- **OpenCV**: For webcam integration and image processing.
- **Streamlit**: For creating the web interface.
- **Numpy**: For numerical operations.
- **Pandas**: For data handling and preprocessing.
- **Matplotlib**: For visualizing performance metrics.

## Model
The project utilizes the VGG16 model, a pre-trained convolutional neural network, to classify ASL gestures. The model has been fine-tuned on the ASL Alphabet Dataset to achieve a high accuracy of 0.99.

## Setup and Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/real-time-sign-language-prediction.git
   cd real-time-sign-language-prediction
   ```

2. **Install the required packages:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Streamlit interface:**
   ```bash
   streamlit run app.py
   ```

## Usage
1. **Open the Streamlit app**: After running the above command, a local URL will be provided.
2. **Allow webcam access**: The app will request permission to access the webcam.
3. **Show ASL gestures**: Show any ASL alphabet gesture (A-Z) in front of the webcam.
4. **Real-time prediction**: The predicted alphabet will be displayed in real-time.

## Performance
The model achieves an accuracy of 0.99 on the test set. Below are some performance metrics and visualizations:

### Accuracy
![Accuracy](images/accuracy.png)

### Loss
![Loss](images/loss.png)

## Interface
### Main Screen
![Main Screen](images/main_screen.png)

### Real-Time Prediction
![Real-Time Prediction](images/real_time_prediction.png)

## Contributing
Contributions are welcome! Please fork this repository and submit pull requests for any features, improvements, or bug fixes.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
- The [ASL Alphabet Dataset](https://www.kaggle.com/datasets/grassknoted/asl-alphabet) provided by GrassKnoted on Kaggle.
- The developers and maintainers of TensorFlow, Keras, OpenCV, and Streamlit for their invaluable tools and libraries.

## Contact
For any inquiries or issues, please open an issue on GitHub or contact the repository owner at [your-email@example.com].

---

Feel free to reach out if you have any questions or need further assistance with the project!
