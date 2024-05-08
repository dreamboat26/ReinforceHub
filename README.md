# Super Mario Bros Lane Detection

This project aims to detect lane lines in a video of a Super Mario Bros game using computer vision techniques. Below is an overview of the process:

## Lane Detection Pipeline

1. **Region Selection**: Define a region of interest in the frame to focus on the road.
2. **Pre-processing**: Convert the frame to grayscale, apply Gaussian blur to reduce noise, and use Canny edge detection to identify edges.
3. **Region Masking**: Apply a mask to focus only on the road region using a polygon.
4. **Hough Transform**: Detect straight lines in the masked region using the Hough transform.
5. **Lane Lines Extraction**: Calculate the slope and intercept of the left and right lane lines.
6. **Drawing Lane Lines**: Draw the detected lane lines on the frame.

## Video Processing

- **Input**: Provide the location of the input video file.
- **Output**: Specify where the output video file with detected lane lines will be saved.

## Usage

1. **Output Video**
2. **Run** 

## Dependencies

- `gym`, `gym-super-mario-bros`: For accessing the Super Mario Bros game environment.
- `stable-baselines3`: Library for reinforcement learning algorithms.
- `opencv-python`: OpenCV library for computer vision tasks.
- `numpy`, `matplotlib`: For numerical computations and visualization.
- `moviepy`: For video processing tasks.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

This project utilizes Gym Super Mario Bros environment, Stable Baselines3, OpenCV, NumPy, and MoviePy libraries for video processing and lane detection.

