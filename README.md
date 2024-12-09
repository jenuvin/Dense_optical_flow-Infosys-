# Dense Optical Flow with Farneback Method

This repository contains a Jupyter Notebook that demonstrates the implementation of **dense optical flow** using the Farneback method in OpenCV. Dense optical flow calculates motion patterns between video frames, making it useful for applications such as motion tracking, object detection, and video stabilization.

## Features

- Implementation of the Farneback method for dense optical flow.
- Real-time processing of video frames to visualize motion.
- Saves processed frames as an output video.
- Visualizations include color-coded representations of motion magnitude and direction.

## Prerequisites

Ensure you have the following installed:

- Python 3.7 or later
- Jupyter Notebook or JupyterLab
- OpenCV
- NumPy

Install the dependencies with pip:

```bash
pip install opencv-python numpy
```

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/dense-optical-flow.git
   cd dense-optical-flow
   ```

2. Add a video file to the `videos/` directory, or modify the file path in the notebook to match your video.

3. Launch the Jupyter Notebook:
   ```bash
   jupyter notebook Dense.ipynb
   ```

4. Follow the instructions in the notebook to:
   - Load your video file.
   - Compute and visualize dense optical flow.
   - Save the output to a new video file.

## Notebook Overview

- **Setup**: Import required libraries and set up video properties.
- **Implementation**: Process video frames and compute optical flow using the Farneback method.
- **Visualization**: Create color-coded visualizations of motion.
- **Output**: Save the processed video with dense optical flow visualization.

## Contributing

Contributions are welcome! Fork the repository and create a pull request to add new features or improvements.

## License

This project is licensed under the [MIT License](LICENSE).

---