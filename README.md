# ASL Finger Spelling
This project implements the mediapipe library and the convolutional neural network model to recognize the American Sign Language alphabets from a video file that contains a word, which is spelled out using the American Sign Language.
The project is not yielding accurate results yet. Working on better accuracy.
The video file is converted into frames and then the frames are extracted at a periodicity of 3s. This inturn requires the user to show different alphabets for every 3s.
Mediapipe is used to detect the wristpoints on the hands and then the image is cropped out. The cropped out image is fed into the CNN model.
The repo only contains the python scripts. The video needs to be recorded and then should be put into appropriate folders.


The word video uploader is an android app that takes the video of required duration depending on the length of the word. The app then uploads it to the local IP address which is hardcoded (working on taking it as the input) as a multipart request.
