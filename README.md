# Underwater obstacle detection
Underwater obstacles and path detection using OpenCV and python. The video is taken from one of the competetions in Singapore AUV Challenge(SAUVC 2013). [Link](https://www.youtube.com/watch?v=H0mIRADzzik) to original video. 

### Pipeline 
The basic pipeline used to detect the obstacles is as follows:

![Screenshot from 2019-12-03 15-13-13](https://user-images.githubusercontent.com/47391270/70039220-93378100-15df-11ea-82e3-cc7b2c162ca5.png)

The code for it is given in the `AUV.ipynb` notebook

### Input video

![](input.gif)

The underwater robot has to follow the black path and avoid the yellow obstacle in between the path. 

### Output

![](final.gif)

### References
1. https://www.pyimagesearch.com/2018/07/19/opencv-tutorial-a-guide-to-learn-opencv/
2. https://medium.com/@galen.ballew/opencv-lanedetection-419361364fc0
3. https://medium.com/@mrhwick/simple-lane-detection-with-opencv-bfeb6ae54ec0
4. https://towardsdatascience.com/deeppicar-part-4-lane-following-via-opencv-737dd9e47c96

