# Stereo-Vision-Disparity-and-Depth-Image
Stereo Vision System

# DESCRIPTION
Structured lighting system for creating high resolution stereo datasets of static indoor scenes with highly accurate ground-truth disparities.

# Pipeline
Pipeline for Stereo Vision
1. Identify matching features between the two images using a feature matching algorithm.
2. Estimate the Fundamental matrix using RANSAC method based on the matched features
3. Compute the Essential matrix from the Fundamental matrix considering calibration parameters
4. Decompose the Essential matrix into rotation and translation matrices
5. Apply perspective transformation to rectify images and ensure horizontal epipolar lines
6. Calculate the disparity map representing the pixel-wise differences between the two images.
7. Utilize the disparity information to compute depth values for each pixel
8. Generate a depth image representing the spatial dimensions of the scene


#Results

Traproom Disparity (Grayscale)          |  Traproom Depth (Heatmap)
:-------------------------:|:-------------------------:
![disparity-BW-2](https://github.com/user-attachments/assets/c4b3ebdb-19ed-4167-a723-34dae91aaf7b) |  ![disparity-clr-2](https://github.com/user-attachments/assets/22c0151e-7029-47c5-b051-25adcafd8789)



Classroom Disparity (Grayscale)             |  Classroom Depth (Heatmap)
:-------------------------:|:-------------------------:
![disparity-BW-3](https://github.com/user-attachments/assets/abe7d5cf-7427-49f8-ac18-81e02d120317)  |  ![disparity-clr-3](https://github.com/user-attachments/assets/68f0a195-5a16-4352-a21d-600cade6eecc)

Storage Room Disparity (Grayscale)             |  Storage Room Depth (Heatmap)
:-------------------------:|:-------------------------:
![disparity-BW-1](https://github.com/user-attachments/assets/31731aa8-a779-4cb5-ac66-17c98477da6e)  |  ![disparity-clr-1](https://github.com/user-attachments/assets/8f50da55-3f66-4560-9c44-a357177827ab)







