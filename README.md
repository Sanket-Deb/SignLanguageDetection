# Sign Language Detection

## Project Description

This project implements a real-time hand gesture recognition system using computer vision and deep learning techniques. It detects and classifies various sign language gestures in real-time using a webcam. Key components include:

- Data loading and preprocessing
- CNN model building and training
- Real-time hand detection and gesture recognition using MediaPipe

## Dataset Details

The dataset used for training is available [here](https://www.kaggle.com/datasets/nikhilgawai/sign-language-dataset). It is stored in a folder named 'sign_language' and includes subfolders for different gestures, each containing JPEG images of the corresponding gesture.

Gestures include:
- thankyou
- yes
- sorry
- sign language
- no
- please
- house
- i_love_you
- help
- family
- hello

The images are preprocessed by resizing them to 64x64 pixels and converting them to RGB format. The dataset is split into training (80%) and testing (20%) sets.
PS (Full Disclosure) - Used Claude AI for some assistance and fine tunning.

## Usage

1. Clone the repository.
2. Train the CNN model on the dataset.
3. Run the real-time detection script using a webcam.

## References

- Tutorial #1: [Link](https://youtu.be/pDXdlXlaCco?si=xFW1CRw9c57ahT-E)
- Tutorial #2: [Link](https://youtu.be/doDUihpj6ro?si=gu1z1x3ou5JDLoqt)

