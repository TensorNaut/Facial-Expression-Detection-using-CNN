# Real-time Expression Detection using Deep Learning

This project demonstrates real-time expression detection using deep learning. It uses a convolutional neural network (CNN) model trained on facial expression images to detect emotions in real-time video streams captured from a webcam.

## Features
- Detects facial expressions in real-time video streams
- Supports multiple expressions such as Angry, Disgust, Fear, Happiness, Sad, Surprise, and Neutral
- Displays predicted emotion labels on the video stream
- Draws rectangles around detected faces for better visualization

## Requirements
- Python 3.x
- OpenCV (`pip install opencv-python`)
- TensorFlow (`pip install tensorflow`)

## Usage
1. Clone this repository:
git clone https://github.com/Tushar-Jagatap/Facial-Expression-Detection-using-CNN.git

2. Navigate to the project directory:
cd Facial-Expression-Detection-using-CNN

3. Run the Python script:
python real_time_run.py

4. Press `q` to exit the program.

## Credits
- The model used in this project is trained using the [FER-2013 dataset](https://www.kaggle.com/deadskull7/fer2013) from Kaggle.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
