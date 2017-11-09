# Lane detection
Lane detection by fully CNN, w/ deep learning.
Please review demo in 
  https://www.youtube.com/watch?v=o5xpxCyRVA0, or
  https://www.youtube.com/watch?v=erF6QPHIrKc.

# Installation
1. install tensorflow. Please refer to tensorflow.org.
2. install jupyter notebook. Please use sudo pip3 install jupyter.
3. install other python libraries.
3. run "jupyter notebook".
4. open "dura_06_det_sam.ipynb".

# Software Requirements
Python 3.5 or higher.

TensorFlow - Suggested to download TensorFlow GPU for best performance.

Keras.

OpenCV (known as cv2 once downloaded) - opencv-python if installing from command line.

h5py.

imageio.

matplotlib.

moviepy.

numpy+mkl.

scikit-learn.

scipy.

# How to train
1. prepare labels
2. run training python commands

# Background
People can find lane lines on the road fairly easily, even in a wide variety of conditions. Unless there is snow covering the ground, extremely heavy rainfall, the road is very dirty or in disrepair, we can mostly tell where we are supposed to go, assuming the lines are actually marked. While some of you reading this may already want to challenge whether other drivers actually succeed at staying within the lines (especially when you want to pass them), even without any driving experience, you know what those yellow and white lines are.
Computers, on the other hand, do not find this easy. Shadows, glare, small changes in the color of the road, slight obstruction of the line…all things that people can generally still handle, but a computer may struggle mightily with. 

# References:
  Canny, J., "A Computational Approach To Edge Detection", IEEE Trans. Pattern Analysis and Machine Intelligence, 1986
  King Hann Lim et al. "Lane-Vehicle Detection and Tracking", IMECS, 2009
