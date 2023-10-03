# Hand Tracking Module

The Hand Tracking Module is a Python library that enables real-time hand tracking and landmark detection using the MediaPipe library and OpenCV. This module provides an easy-to-use interface for developers to integrate hand tracking functionality into their projects, applications, or computer vision tasks.

![Hand Tracking Example](https://github.com/Ahmad10Raza/HandTrackingModule/blob/master/hand.svg)

## Features

- Real-time hand tracking: Detect and track the movement of one or more hands in live video or image streams.
- Hand landmark detection: Retrieve the coordinates of key landmarks on detected hands, including fingertips, knuckles, and palm centers.
- Easy integration: The module is designed for ease of use, making it suitable for a wide range of applications.
- Customizable: Configure tracking parameters and visualize landmarks to suit your specific needs.

## Getting Started

To get started with the Hand Tracking Module, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/Ahmad10Raza/HandTrackingModule.git
   ```

2. Install the required dependencies:

   ```bash
   pip install mediapipe opencv-python
   ```

3. Import the module into your Python script:

   ```python
   import HandTrackingModule as htm
   ```

4. Initialize the `HandTracker` class and start tracking hands in your video stream or images.

   ```python
   # Example usage
   detector = htm.handDetector()
   ```

   Check the `Example.py` file in this repository for a basic usage example.

## Usage

The Hand Tracking Module offers straightforward usage to enable hand tracking in your projects. Refer to the [documentation](DOCUMENTATION.md) for detailed instructions, API reference, and usage examples.

## Contributing

Contributions to this project are welcome! Feel free to open issues, suggest improvements, or submit pull requests. Please refer to the [contribution guidelines](CONTRIBUTING.md) for more information.


## Acknowledgments

- Special thanks to the MediaPipe team for their excellent library, which makes hand tracking accessible to developers.
- Special thanks to [Murtaza Hassan](https://www.murtazahassan.com/) (YouTuber) for their excellent teaching style that make CV very easy to understand.

Happy hand tracking!
