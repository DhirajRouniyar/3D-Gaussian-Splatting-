# 3D-Gaussian-Splatting-
An implementation of paper [3D Gaussian Splatting for Real-Time Radiance Field Rendering](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/).  
The algorithm takes image from multiple views, a sparse point cloud, and camera pose as input, use a differentiable rasterizer to train the point cloud, and output a dense point cloud with extra features(covariance, color information, etc.). Refer my [Drive-link]() to get the 
[dataset](https://drive.google.com/drive/folders/1FfYRrKjHXwqhbaOIGE1_AspUxMOWXqmN?usp=sharing), 
[trained output logs (.parquet)](https://drive.google.com/drive/folders/1fnJib6JGTc9BAMBZIpcgKRhYR-L3o5Wn?usp=sharing), 
[event for Tensorboard](https://drive.google.com/file/d/1rEgp3nYl6l-JG8jQyG5fybu5JF_Ei_9r/view?usp=sharing) and 
[Results](https://drive.google.com/drive/folders/1grh0cva9WUlQwC5ljeca-hEmrWze8yUJ?usp=sharing).

# Train Steps-

![alt text](https://github.com/DhirajRouniyar/3D-Gaussian-Splatting-/blob/main/Output/Train_steps_Gaussian_Splatting.png)

# Results-

![alt text](https://github.com/DhirajRouniyar/3D-Gaussian-Splatting-/blob/main/Output/Output_Gaussian_Splatting_.gif)

#Train/Loss Graph-

![alt text](https://github.com/DhirajRouniyar/3D-Gaussian-Splatting-/blob/main/Output/Loss%20graph.png)

#Train/PSNR Graph-

![alt text](https://github.com/DhirajRouniyar/3D-Gaussian-Splatting-/blob/main/Output/PSNR%20graph.png)
