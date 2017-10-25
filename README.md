# lanedetection
Lane detection by fully CNN, w/ deep learning.
Please review demo in https://www.youtube.com/watch?v=hvHbGirikBI.
Presented by Dura Automotive Systems, more on www.duraauto.com.

# installation
1. install tensorflow. Please refer to tensorflow.org.
2. install jupyter notebook. Please use sudo pip3 install jupyter.
3. install other python libraries.
3. run "jupyter notebook".
4. open "dura_06_det_sam.ipynb".

# how to train
1. prepare labels
2. run training python commands

# background
People can find lane lines on the road fairly easily, even in a wide variety of conditions. Unless there is snow covering the ground, extremely heavy rainfall, the road is very dirty or in disrepair, we can mostly tell where we are supposed to go, assuming the lines are actually marked. While some of you reading this may already want to challenge whether other drivers actually succeed at staying within the lines (especially when you want to pass them), even without any driving experience, you know what those yellow and white lines are.
Computers, on the other hand, do not find this easy. Shadows, glare, small changes in the color of the road, slight obstruction of the line…all things that people can generally still handle, but a computer may struggle mightily with. 
