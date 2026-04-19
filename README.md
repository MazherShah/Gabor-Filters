# Gabor-Filters
This project demonstrates the use of Gabor filters for image analysis and feature extraction using Python and OpenCV. The notebook explores applying Gabor filters to general images, multi-orientation filtering, and a specific use case: fingerprint enhancement.

🧠 Overview

Gabor filters are widely used in computer vision for:

Texture analysis
Edge detection
Pattern recognition
Biometric applications (e.g., fingerprint enhancement)

They work by applying sinusoidal waves modulated by a Gaussian function, allowing detection of spatial frequency and orientation-specific features.

📂 Notebook Structure

The notebook contains three main experiments:

1. Basic Gabor Filter Application
Upload an image (grayscale or color)
Convert to grayscale
Apply a single Gabor filter with fixed parameters
Visualize the filtered result

Key Parameters:

ksize: Kernel size
sigma: Gaussian standard deviation
theta: Orientation
lambda: Wavelength
gamma: Aspect ratio
2. Multi-Orientation Gabor Filtering
Applies Gabor filters at multiple orientations:
0°
45°
90°
135°
Displays results side-by-side

Purpose:
To show how orientation affects feature extraction and highlights directional textures.

3. Fingerprint Enhancement
Upload a fingerprint image
Apply Gabor filters tuned for ridge patterns
Enhances fingerprint clarity for further processing

Use Case:
Biometric systems and pattern recognition

⚙️ Requirements

Install the following Python libraries:

pip install opencv-python numpy matplotlib

If running in Google Colab, no installation is required.

▶️ How to Run
Open the notebook in Google Colab
Run each cell sequentially
Upload an image when prompted

Supported inputs:

Textures
Faces
Fabrics
Fingerprints
