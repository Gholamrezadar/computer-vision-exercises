# Computer Vision (CV) Exercises
Computer Vision Course Exercises at Amirkabir University of Technology - Fall 2022

By Gholamreza Dar

# Content
- Table of Contents
  * [Exercise 1](#exercise-1)
  * [Exercise 2](#exercise-2)
  * [Exercise 3](#exercise-3)
  * [Exercise 4](#exercise-4)
  * [Exercise 5](#exercise-5)
  * [Exercise 6](#exercise-6)
  * [Exercise 7](#exercise-7)
  * [Exercise 8](#exercise-8)
  

## Exercise 1

- Fundamental image manipulations
- Extract colors using HSV colorspace and `inRange()` function
- Align and Combine misaligned channels
<img style="width:600px" src="https://github.com/Gholamrezadar/computer-vision-exercises/blob/main/Tahvil%20Tamrin%20CV/results/1-alignment.jpg?raw=true"/>
- Canny edge detection practice
- Histogram Equalization using RGB vs YUV color spaces
<img style="width:600px" src="https://github.com/Gholamrezadar/computer-vision-exercises/blob/main/Tahvil%20Tamrin%20CV/results/Histogram_Equalization_RGB.jpg?raw=true"/>

<img style="width:600px" src="https://github.com/Gholamrezadar/computer-vision-exercises/blob/main/Tahvil%20Tamrin%20CV/results/Histogram_Equalization_YUV.jpg?raw=true"/>

## Exercise 2

- Road Lane Detection
    * Detect road lanes using Canny, Hough, Clustering lines by angle, and Linear regression
<img style="width:600px" src="https://github.com/Gholamrezadar/computer-vision-exercises/blob/main/Tahvil%20Tamrin%20CV/results/2-lanes.jpg?raw=true"/>

 - Road Lane Detection on video
    * Added smoothing features to maintain the lanes over time (Some frames were very blurry or foggy, but we could assume that the car doesn't suddenly change directions).
  
  video
  
  video
  
- Crack Segmentation using Active Contours
<img style="width:400px" src="https://github.com/Gholamrezadar/computer-vision-exercises/blob/main/Tahvil%20Tamrin%20CV/results/2-active.jpg?raw=true"/>

## Exercise 3

- Implement Otsu Thresholding
- Implement Iterative Thresholding
- Match Template Exercise
   * Detect the template in various orientations by rotating the template each time.
<img style="width:400px" src="https://github.com/Gholamrezadar/computer-vision-exercises/blob/main/Tahvil%20Tamrin%20CV/results/3-matching.jpg?raw=true"/>

 ## Exercise 4
 
 - Colored-Image Segmentation by Clustering
<img style="width:600px" src="https://github.com/Gholamrezadar/computer-vision-exercises/blob/main/Tahvil%20Tamrin%20CV/results/4-clusteringseg.jpg?raw=true"/>

 - Image Segmentation using [GLCM](https://scikit-image.org/docs/stable/auto_examples/features_detection/plot_glcm.html)
<img style="width:600px" src="https://github.com/Gholamrezadar/computer-vision-exercises/blob/main/Tahvil%20Tamrin%20CV/results/onion_zebra.png?raw=true"/>
 
 - Image Segmentation using Filter Banks
<img style="width:600px" src="https://github.com/Gholamrezadar/computer-vision-exercises/blob/main/Tahvil%20Tamrin%20CV/results/4-filterbanks.jpg?raw=true"/>

<img style="width:600px" src="https://github.com/Gholamrezadar/computer-vision-exercises/blob/main/Tahvil%20Tamrin%20CV/results/4-filterbanks_results.jpg?raw=true"/>

## Exercise 5
 
 - Feature Matching using SIFT
    * Recover a rotated Image using feature matching
<img style="width:600px" src="https://github.com/Gholamrezadar/computer-vision-exercises/blob/main/Tahvil%20Tamrin%20CV/results/5-siftresult.jpg?raw=true"/>
 
 - Compare SIFT and FREAK
<img style="width:600px" src="https://github.com/Gholamrezadar/computer-vision-exercises/blob/main/Tahvil%20Tamrin%20CV/results/sift_vs_freak.jpg?raw=true"/>

## Exercise 6
 
 - Object Detection on the Counter-Strike dataset (R-CNN method)
    + Classes are: W(eapon), T(errorist), C(ounter terrorist), D(ead), bg
    + using mean (average) of a patch as the feature and KNN as classifier
<img style="width:600px" src="https://github.com/Gholamrezadar/computer-vision-exercises/blob/main/Tahvil%20Tamrin%20CV/results/6-mean-results.jpg?raw=true"/>
    
+ using LBP (Local Binary Pattern) of a patch as the feature and KNN as classifier
<img style="width:600px" src="https://github.com/Gholamrezadar/computer-vision-exercises/blob/main/Tahvil%20Tamrin%20CV/results/6-lbp-results.jpg?raw=true"/>
   
+ using Neural Network (EfficientNetb0) as the feature extractor and classifier
<img style="width:600px" src="https://github.com/Gholamrezadar/computer-vision-exercises/blob/main/Tahvil%20Tamrin%20CV/results/6-cnn-results.jpg?raw=true"/>
   
<img style="width:600px" src="https://github.com/Gholamrezadar/computer-vision-exercises/blob/main/Tahvil%20Tamrin%20CV/results/5-sift_vs_freak.jpg?raw=true"/>

+ Some of the results (Can definitely be improved but due to the end-of-semester time limits didn't try to improve it).
    
<img style="width:600px" src="https://github.com/Gholamrezadar/computer-vision-exercises/blob/main/Tahvil%20Tamrin%20CV/results/5-sift_vs_freak.jpg?raw=true"/>

  ## Exercise 7

 - 3D Vision
    * Plotting LiDAR data on the image using the camera parameters
<img style="width:600px" src="https://github.com/Gholamrezadar/computer-vision-exercises/blob/main/Tahvil%20Tamrin%20CV/results/7-lidar_plot_points.jpg?raw=true"/>

    * Using LiDAR data to estimate the depth map
<img style="width:600px" src="https://github.com/Gholamrezadar/computer-vision-exercises/blob/main/Tahvil%20Tamrin%20CV/results/7-lidar-line_project.jpg?raw=true"/>

    * Using Linear Interpolation to overcome the sparsity of LiDAR data
<img style="width:600px" src="https://github.com/Gholamrezadar/computer-vision-exercises/blob/main/Tahvil%20Tamrin%20CV/results/7-lerp.jpg?raw=true"/>

    * Using stereo matching to estimate the depth map
<img style="width:600px" src="https://github.com/Gholamrezadar/computer-vision-exercises/blob/main/Tahvil%20Tamrin%20CV/results/7-stereo.jpg?raw=true"/>

    * 3D reconstruction of the scene using the estimated depth map
<img style="width:600px" src="https://github.com/Gholamrezadar/computer-vision-exercises/blob/main/Tahvil%20Tamrin%20CV/results/7-3dreconstruction.jpg?raw=true"/>


## Exercise 8
 - Detect Corners using Shi-Tomas Algorithm
<img style="width:600px" src="https://github.com/Gholamrezadar/computer-vision-exercises/blob/main/Tahvil%20Tamrin%20CV/results/8-shi-tomas.jpg?raw=true"/>

 - Optical Flow using the Lukas-Kanade Algorithm
<img style="width:600px" src="https://github.com/Gholamrezadar/computer-vision-exercises/blob/main/Tahvil%20Tamrin%20CV/results/8-lukas.jpg?raw=true"/>

 - Dense Optical Flow using the Gunnar-Farneback Algorithm
<img style="width:600px" src="https://github.com/Gholamrezadar/computer-vision-exercises/blob/main/Tahvil%20Tamrin%20CV/results/8-gunner.jpg?raw=true"/>

<img style="width:600px" src="https://github.com/Gholamrezadar/computer-vision-exercises/blob/main/Tahvil%20Tamrin%20CV/results/8-gunner-hsv.jpg?raw=true"/>
