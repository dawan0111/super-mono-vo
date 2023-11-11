# SuperPoint Visual Odometry Project

## Project Overview

This project leverages the SuperPoint deep learning model to implement visual odometry, a technique for estimating a robot or vehicle's path through image sequences captured by a camera. SuperPoint excels in detecting keypoints and descriptors, enabling high-accuracy tracking in this project.

## Key Features

- **SuperPoint Keypoint Detection**: Rapid and precise identification of interest points within images.
- **Optical Flow for Feature Matching**: Tracking the movement across image sequences through robust feature matching using Optical Flow.
- **Path Estimation**: Estimation of camera movement and trajectory based on matching information.
- **Real-time Processing**: Real-time tracking support through the optimization of SuperPoint and the visual odometry algorithm.

## Installation
```bash
mkdir build
cd build
cmake ..
make
```

## Examples
![(https://i.postimg.cc/Kv8GL63M/2023-09-01-11-50-32.png)](https://i.postimg.cc/Kv8GL63M/2023-09-01-11-50-32.png)

## Video Link
[![Video Link](https://i.postimg.cc/y8rkkVfx/2023-11-11-6-03-01.png)](https://youtu.be/vYlqADv2Alk)


## License
MIT
