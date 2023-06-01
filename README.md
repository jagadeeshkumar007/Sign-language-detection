# Sign Language Detection

The Sign Language Detection project aims to identify sign language gestures using deep learning techniques. The project utilizes the `SSD MobileNet` model for detection and employs TensorFlow for image processing. It has been trained on a custom dataset, labeled by hand, for 20,000 epochs. For real-time predictions, the project utilizes checkpoint 21.I trained the model for 5 classes, they are `hello, yes, no, thankyou, i love you`.

## Features

- **Sign Language Gesture Identification**: The system can identify and classify sign language gestures in real-time.

- **SSD MobileNet Model**: The project utilizes the SSD MobileNet model, a deep learning-based object detection algorithm, for accurate gesture detection.

- **TensorFlow Integration**: TensorFlow is used for image processing and the implementation of the deep learning model.

- **Custom Dataset**: The model has been trained on a custom dataset specifically collected for sign language gestures, with labels applied manually.

## Installation

To set up the Sign Language Detection project locally, follow these steps:

1. Clone the repository:

   ```shell
   git clone https://github.com/your-username/sign-language-detection.git
2. To create custom dataset go through the `data_collection.ipynb` notebook and label them using `labelImg` to use it go through `Tensorflow/labelImg`.
3. To train the model go through `sign_language_detection.ipynb` notebook and follow the steps.
4. To see the images go through `Tensorflow/workspace/images` directory.
5. To see the models go through `Tensorflow/workspace/models` directory.
6. To see the checkpoints go through`Tensorflow/workspace/models/my_ssd_mobnet` directory.
## Usage
1. Launch the project and ensure your camera is connected or provide an image for sign language detection.

2. The system will detect sign language gestures in the video or image and provide the corresponding classification.

3. The detected gestures will be annotated with labels indicating the identified sign language.

4. Observe the real-time sign language detection or analyze the results from the provided image.

5. Experiment with different gestures and hand positions to evaluate the model's performance.
