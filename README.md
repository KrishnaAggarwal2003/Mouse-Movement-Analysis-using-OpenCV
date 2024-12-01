# Mouse-Movement-Analysis-using-OpenCV

## Introduction
This project focuses on analyzing mouse movement within a video using OpenCV. The video is processed to track the mouse's activity across three predefined boxes placed at the beginning of three lanes. By monitoring changes in pixel intensity within these boxes, the program determines the number of times the mouse crosses into and out of the lanes during the video.

The code recreates the video with the added visual overlay of the boxes and performs detailed analysis by plotting the intensity changes for each box throughout the video duration. Additionally, derivative plots of the intensity are generated to capture rate-of-change trends, providing insights into the dynamics of the mouse's movement. To further refine the analysis, the code incorporates denoising in the intensity plots using a threshold value, effectively filtering out noise and improving the accuracy of the results.

This comprehensive approach combines visualization and analysis, making it a valuable tool for studying mouse movement behavior in video-based experiments.

### The original video
