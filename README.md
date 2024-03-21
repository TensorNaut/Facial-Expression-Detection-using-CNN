<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Real-time Expression Detection using Deep Learning</title>
</head>
<body>
    <h1>Real-time Expression Detection using Deep Learning</h1>
    <p>This project demonstrates real-time expression detection using deep learning. It uses a convolutional neural network (CNN) model trained on facial expression images to detect emotions in real-time video streams captured from a webcam.</p>

    <h2>Features</h2>
    <ul>
        <li>Detects facial expressions in real-time video streams</li>
        <li>Supports multiple expressions such as Angry, Disgust, Fear, Happiness, Sad, Surprise, and Neutral</li>
        <li>Displays predicted emotion labels on the video stream</li>
        <li>Draws rectangles around detected faces for better visualization</li>
    </ul>

    <h2>Requirements</h2>
    <ul>
        <li>Python 3.x</li>
        <li>OpenCV (`pip install opencv-python`)</li>
        <li>TensorFlow (`pip install tensorflow`)</li>
    </ul>

    <h2>Usage</h2>
    <ol>
        <li>Clone this repository:</li>
    </ol>
    <pre><code>git clone https://github.com/Tushar-Jagatap/Facial-Expression-Detection-using-CNN.git</code></pre>
    <ol start="2">
        <li>Navigate to the project directory:</li>
    </ol>
    <pre><code>cd Facial-Expression-Detection-using-CNN</code></pre>
    <ol start="3">
        <li>Run the Python script:</li>
    </ol>
    <pre><code>python expression_detection.py</code></pre>
    <ol start="4">
        <li>Press <code>q</code> to exit the program.</li>
    </ol>

    <h2>Credits</h2>
    <ul>
        <li>The model used in this project is trained using the <a href="https://www.kaggle.com/deadskull7/fer2013">FER-2013 dataset</a> from Kaggle.</li>
    </ul>

    <h2>License</h2>
    <p>This project is licensed under the MIT License - see the <a href="LICENSE">LICENSE</a> file for details.</p>
</body>
</html>
