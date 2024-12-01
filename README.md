# Mouse-Movement-Analysis-using-OpenCV

## Introduction
This project focuses on analyzing mouse movement within a video using OpenCV. The video is processed to track the mouse's activity across three predefined boxes at the beginning of three lanes. By monitoring changes in pixel intensity within these boxes, the program determines the number of times the mouse crosses into and out of the lanes during the video.

The code recreates the video with the added visual overlay of the boxes and performs detailed analysis by plotting each box's intensity changes throughout the duration. Additionally, derivative plots of the intensity are generated to capture rate-of-change trends, providing insights into the dynamics of the mouse's movement. To further refine the analysis, the code incorporates denoising in the intensity plots using a threshold value, effectively filtering out noise and improving the accuracy of the results.

This comprehensive approach combines visualization and analysis, making it a valuable tool for studying mouse movement behaviour in video-based experiments.

### The original video
![The original data gif](https://github.com/KrishnaAggarwal2003/Mouse-Movement-Analysis-using-OpenCV/blob/main/Initial_video_gif.gif)

### Video with boxes added using OpenCV
![With boxes gif](https://github.com/KrishnaAggarwal2003/Mouse-Movement-Analysis-using-OpenCV/blob/main/With-boxes_video_gif.gif)

## The analysis Plots
### The intensity plot
- Original plot
![intensity](https://github.com/user-attachments/assets/2489b789-7107-4a17-8e6b-ca97d1de4950)
- Plot after denoising the data
![denoise](https://github.com/user-attachments/assets/68014877-eb5a-4321-ae6c-2ec330c20fd0)

### Intensity derivative plots
- Original data derivative plot
![before](https://github.com/user-attachments/assets/ba6ebeb7-e041-43d5-a9f2-c9ccefbb8ec6)
- After denoising
![after](https://github.com/user-attachments/assets/914c90ec-7145-4501-996c-f4343b85a127)


