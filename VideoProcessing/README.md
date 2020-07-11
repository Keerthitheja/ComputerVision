# Video Processing

## Requirements
```
- OpenCV Python : 4.1.0
- ImUtils : 0.5.3
- Numpy : 1.18.1
```
## Performing basic computer Vision techniques on video frames. 

In this project, image frames from a video are read and some of the computer vision techniques are applied on each image frame. Multiple processed image frames are then stitched into a single frame and a 60 secs video is created out of those processed frames.

The .ipynb file [Video_Processing.ipynb](Video_Processing.ipynb) has the python code that reads a input video file available at [Source Video File Folder](SourceVideoFile/InputVideoFile.mp4)

Various Image Processing techniques are applied on the video frames for a certain duration of the video.

### 0 to 20 secs:

For the first 0 to 20 secs, image filters like Gaussian, median and morphological filters are applied on each frame. Edge Features are also extracted using edge detection filters.


### 21 to 40 secs:

Next 20 secs, techniques like circle detection using Hough transform,  object detection and template matching etc are applied on the object in the video frame  

### 41 to 60 secs:

During the last 20 secs, techniques like object tracking, object changing colors and the object in the video frame is made invisible.

The final ouput video can be seen here 

![](OutputVideoFile/output.gif)
