# Deep-Fake detection

This Model takes a video as input and predicts if the video is fake.
The prediction is only based on the first frame of the video.

The model contains a simple stack of 3 convolution layers with a ReLU activation and followed by max-pooling layers.

<b>The accuracy of the model is about 70%.</b>

The dataset is available <a href="https://www.kaggle.com/c/deepfake-detection/data">here</a>
