# Project Adam - Equestrian Artifical Intelligence Algorithm

Project Adam is a project for processing video's and classifying them with the starting code base as an activity recognition problem with CNN & LSTM/RNN based upon an Inception 3 framework and TensorFlow/Keras. The future stages will also aim to use the same video to produce 3d pose estimation and YOLO.

The ultimate goal of project adam is to use this framework to record an equestrian athlete performing certain techniques, assign them to a class (0-1, 0-9; 0 is worst 9 is the best), and then process the same video stream through a series of different classification problems that I will define correctly later. Then we will parse the processed videos together to create a profile of the athlete on a given day.

The initial goal is simple and straight forward. We have 2 classes of videos of a horse cantering and trotting and we will need to develop and execute a standalone training routine for the algorithms to learn from these videos. Then we will take a single video file, load it into a folder, and then launch the algorithm to create the predictions. These predictions will be written out to a dataframe to be used for further analytics. 

Once we get the core mechanics working, we will focus on optimizing and improving the prediction accuracy. Maybe even create supporting tools and structures around thi? (Potentially we can rebuild the CNN into a 3D Convolutional Net or create alternate 2 stream approaches.) I will showcase any developments on my end around this work to the community.

The existing model training/testing and prediction routines are located in the following folder: \Project_Adam\Production_Algorithm\Classification

Please feel free to contact me directly at derek.m.kane@gmail.com regarding the aim of this project and I certainly appreciate any contributions to the effort. Knowledge is power and lets work together to figure this out. Many different applications can come out of this and lets share the wealth... Carpe Diem!
