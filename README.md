# Drowsness-Detection-System
With this Python project, we will be making a drowsiness detection system. A countless number of people drive on the highway day and night. Taxi drivers, bus drivers, truck drivers and people traveling long-distance suffer from lack of sleep. Due to which it becomes very dangerous to drive when feeling sleepy.
The majority of accidents happen due to the drowsiness of the driver. So, to prevent these accidents we will build a system using Python, OpenCV, and Keras which will alert the driver when he feels sleepy.
we will be using OpenCV for gathering the images from webcam and feed them into a Deep Learning model which will classify whether the person’s eyes are ‘Open’ or ‘Closed’. The approach we will be using for this Python project is as follows :

<br/>Step 1 – Take image as input from a camera.
<br/>Step 2 – Detect the face in the image and create a Region of Interest (ROI).
<br/>Step 3 – Detect the eyes from ROI and feed it to the classifier.
<br/>Step 4 – Classifier will categorize whether eyes are open or closed.
<br/>Step 5 – Calculate score to check whether the person is drowsy.
