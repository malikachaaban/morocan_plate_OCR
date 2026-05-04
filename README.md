# 🇲🇦 Moroccan License Plate OCR

<div align="center">

[![GitHub stars](https://img.shields.io/github/stars/malikachaaban/morocan_plate_OCR?style=for-the-badge)](https://github.com/malikachaaban/morocan_plate_OCR/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/malikachaaban/morocan_plate_OCR?style=for-the-badge)](https://github.com/malikachaaban/morocan_plate_OCR/network)
[![GitHub issues](https://img.shields.io/github/issues/malikachaaban/morocan_plate_OCR?style=for-the-badge)](https://github.com/malikachaaban/morocan_plate_OCR/issues)

**An end-to-end Optical Character Recognition (OCR) system designed specifically for the detection and recognition of Moroccan vehicle license plates.**

</div>

## 📖 Overview

This project presents a comprehensive solution for Optical Character Recognition (OCR) applied to Moroccan vehicle license plates. Utilizing a Jupyter Notebook, it outlines the entire pipeline from image preprocessing and license plate detection to character segmentation and final character recognition. The system is engineered to accurately extract textual information from the unique format of Moroccan license plates, offering a foundational tool for applications in traffic management, surveillance, and automated vehicle systems.

## ✨ Features

-   **Moroccan Plate Detection**: Robust algorithms for accurately locating license plates within various image contexts.
-   **Character Segmentation**: Precise isolation of individual digits and letters from the detected license plate.
-   **Optical Character Recognition (OCR)**: Deep learning-based models for high-accuracy recognition of segmented characters.
-   **Image Preprocessing Pipeline**: Steps to enhance image quality and optimize plates for detection and recognition.
-   **Interactive Analysis**: All steps are presented within a Jupyter Notebook, allowing for easy understanding, modification, and execution of the workflow.
-   **Flexible Architecture**: Designed for potential integration into broader computer vision applications.

## 🛠️ Tech Stack

**Language & Environment:**

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)

[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)

**Core Libraries:**

[![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)](https://opencv.org/)

[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)](https://www.tensorflow.org/)

[![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)](https://keras.io/)

[![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org/)

[![Matplotlib](https://img.shields.io/badge/Matplotlib-2E6F2F?style=for-the-badge&logo=matplotlib&logoColor=white)](https://matplotlib.org/)

## 🚀 Quick Start

Follow these steps to set up and run the Moroccan License Plate OCR project.

### Prerequisites

Before you begin, ensure you have the following installed:
-   **Python 3.8+**
-   **pip** (Python package installer) or **Conda**

### Installation

1.  **Clone the repository**
    ```bash
    git clone https://github.com/malikachaaban/morocan_plate_OCR.git
    cd morocan_plate_OCR
    ```

2.  **Create and activate a virtual environment** (recommended)
    ```bash
    python -m venv venv
    # On Windows
    .\venv\Scripts\activate
    # On macOS/Linux
    source venv/bin/activate
    ```
    *Alternatively, with Conda:*
    ```bash
    conda create -n moroccan_ocr python=3.9 # Or your preferred Python version
    conda activate moroccan_ocr
    ```

3.  **Install dependencies**
    Since there isn't a `requirements.txt` file, you will need to install the commonly used libraries for this project manually. The `moroccan_plates_OCR.ipynb` notebook itself will show the exact imports, but here are the most likely ones:

    ```bash
    pip install jupyter numpy opencv-python tensorflow keras matplotlib pillow
    ```
    *(Note: `opencv-python` is the common package name for OpenCV. `tensorflow` includes Keras.)*

### Usage

1.  **Start Jupyter Notebook**
    From the project root directory, launch Jupyter:
    ```bash
    jupyter notebook
    ```

2.  **Open the notebook**
    In your browser, navigate to and open `moroccan_plates_OCR.ipynb`.

3.  **Run the cells**
    Execute the notebook cells sequentially to walk through the entire OCR pipeline:
    -   Data loading and preprocessing.
    -   License plate detection.
    -   Character segmentation.
    -   OCR model inference and result display.

## 📁 Project Structure

```
morocan_plate_OCR/
├── moroccan_plates_OCR.ipynb   # Main Jupyter Notebook containing all code and analysis
├── README.md                   # This README file
```
## ⚙️ Configuration

All configuration parameters, such as model hyperparameters, image processing thresholds, and file paths for datasets, are defined directly within the `moroccan_plates_OCR.ipynb` notebook cells. You can modify these values directly in the notebook to experiment with different settings.

## 🙏 Acknowledgments

-   This project leverages the power of **OpenCV** for image processing, **TensorFlow/Keras** for deep learning, and **Jupyter Notebook** for interactive development.
-   Inspired by the challenges of computer vision in specific regional contexts.

<div align="center">

**⭐ Star this repo if you find it helpful!**


</div>


