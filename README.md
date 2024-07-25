# Computer-Aided-Monitoring-System-for-Alzheimer-s-Disease-based-on-MRI-images

## Overview

The **Computer Aided Monitoring System** is a software application designed to assist medical practitioners in tracking the progression of Alzheimer's disease in patients through MRI image analysis. The system provides tools to compare MRI images over time and assess changes that may indicate the progression of the disease.

## Features

- **Upload MRI Images:** Allows users to upload MRI images of patients for analysis.
- **Progress Tracking:** Compares MRI images to monitor disease progression.
- **Alzheimer's Disease Information:** Provides detailed information about Alzheimer's disease, including symptoms, causes, and treatment options.
- **Visual Representation:** Displays processed MRI images and relevant metrics.

## Installation

To get started with the Computer Aided Monitoring System, follow these steps:

1. **Clone the Repository**

   ```bash
   git clone https://github.com/adiba-kazi/Computer-Aided-Monitoring-System.git
   cd Computer-Aided-Monitoring-System
   ```

2. **Set Up the Environment**

   The project uses Python and requires the following libraries:

   - `numpy`
   - `opencv-python`
   - `matplotlib`
   - `ipywidgets`
   - `google-colab` (for file uploads in Colab)

   Install the required libraries using `pip`:

   ```bash
   pip install numpy opencv-python matplotlib ipywidgets google-colab
   ```

3. **Run the Application**

   Open a Jupyter Notebook or Google Colab environment and execute the provided Python script to start using the application. Ensure that you have the necessary MRI images ready for upload.

## Usage

1. **Upload MRI Images**
   - Navigate to the "Check Progress" section.
   - Use the provided buttons to upload MRI images for analysis.

2. **Compare Images**
   - After uploading, use the "Compare Images" button to process and compare the MRI images.

3. **View Alzheimer's Information**
   - Access the "Alzheimer Info" section to read detailed information about Alzheimer's disease.

## Code Explanation

- **Image Processing:** Utilizes OpenCV to preprocess MRI images, including Gaussian blurring and binary conversion.
- **Metrics Calculation:** Computes metrics such as total pixels, white pixels, and black pixels to assess image changes.
- **Progress Comparison:** Analyzes differences between two MRI images to determine disease progression.

## Contributing

Contributions to the Computer Aided Monitoring System are welcome. To contribute:

1. Fork the repository.
2. Create a new branch for your changes.
3. Commit your changes and push to your fork.
4. Open a pull request.

## Contact

For any questions or feedback, please contact:

Name: Adiba Kazi
Email: aikazi8857@gmail.com
GitHub: adiba-kazi
---
