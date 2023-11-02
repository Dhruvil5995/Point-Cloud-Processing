# Depth Image and Point Cloud Processing in Python

This repository is dedicated to the exploration and processing of depth images and the subsequent analysis of point clouds. It leverages powerful Python libraries such as OpenCV, NumPy, Matplotlib, and Open3D to handle complex operations in image processing and 3D data visualization.

## Getting Started

Before you dive into the scripts, ensure you have the following prerequisites:

- Python 3.6 or above
- Libraries: NumPy, Open3D, scikit-learn, Matplotlib

## Repository Contents

Here's what you'll find in this repository:

### Scripts for Visualization and Analysis

- `point_cloud_visualization.py`: A robust script for crafting and exhibiting point clouds. It features a variety of methods for point cloud generation and display, covering everything from RGB-D image processing to mesh sampling and random 3D array creation.

  - Visualize point clouds from different data sources.
  - Convert RGB and depth images into a structured point cloud format.
  - Exhibit point clouds using Open3D and Matplotlib for in-depth analysis.
![matlab_vis](https://user-images.githubusercontent.com/85798077/234074025-d48b5a83-99d5-489e-b5dd-b39458b7f032.png)
![bunny_matplot](https://user-images.githubusercontent.com/85798077/234074057-093feca4-f26a-472b-9fa3-5d261243bdd0.png)


https://user-images.githubusercontent.com/85798077/234074068-8391188a-7c70-4790-bc99-2a353234fc69.mp4



https://user-images.githubusercontent.com/85798077/234074084-c640d525-062a-42e0-8327-dd6506036c3c.mp4

- `point_cloud_filtering.py`: Demonstrates the art of point cloud filtration. This script includes procedures for subsampling and outlier removal, improving point cloud quality for better analysis results.

  - Techniques include random, uniform, and voxel downsampling.
  - Outlier removal methods to refine the point cloud data.

- `ground_detection.py`: An effective script for isolating and highlighting ground surfaces in depth images.

  - Detect and colorize ground pixels within depth images for clearer ground segmentation.

- `point_cloud_segmentation.py`: Implements clustering on point cloud data to segment and differentiate between various object clusters.

  - Uses DBSCAN algorithm for identifying distinct clusters within the point cloud.
 
  -![Ground_Detection](https://user-images.githubusercontent.com/85798077/234078206-755ecb78-4828-47a0-9a3e-0a3b9e26f39b.png) 

## Installation

Clone the repository and install the dependencies to get started:

```sh
git clone [https://github.com/Dhruvil5995/Point-Cloud-Processing]
pip install -r requirements.txt
```

Make sure you're set up with the correct Python version and have all the required libraries installed.

## Usage

- Import the necessary modules from the scripts into your project.
- Utilize the classes and methods provided to process depth images and analyze point clouds.
- Visualize and segment point clouds for further robotic perception or computer vision tasks.


Additionally, `Ground_Detection` provides a visual insight into how the ground detection algorithm segments the ground area within a depth image.

