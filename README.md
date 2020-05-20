# Real Time Gesture Detection to Simulate Guitar Chords

Two models working in conjunction:

* Training hand detection with ssd-mobilenet
* Custom data and model to detect the gesture after hand is detected to play the corresponding chord shown

Hand Dataset from Oxford used for the first model with ssd-mobilenet, and custom dataset with images of guitar chords used for the keras model.

Built with OpenCV, TensorFlow and Keras with TensorFlow backend.
