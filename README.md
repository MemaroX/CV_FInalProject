# Handwritten Digit Recognition: A Computer Vision Final Project

This project implements a neural network model to classify handwritten digits using the MNIST dataset. It was developed as a **final project for a Computer Vision course** and achieved a score of **93%**, demonstrating a strong understanding of machine learning and deep learning fundamentals in the context of image classification.

## Overview

This project explores the end-to-end process of building and evaluating a deep learning model for image classification. It covers data preprocessing, neural network architecture design, model training, and performance evaluation, providing a solid foundation for more advanced computer vision tasks.

## Features

-   **Handwritten Digit Classification:** Accurately recognizes digits (0-9) from handwritten images.
-   **Neural Network Model:** Implements a deep learning model using TensorFlow and Keras.
-   **Data Preprocessing:** Includes steps for preparing image data for model training.
-   **Model Training & Evaluation:** Demonstrates the training process and evaluates model performance using standard metrics.
-   **Interactive Analysis:** Utilizes Jupyter Notebook for step-by-step code execution, visualization, and analysis.

## Technologies Used

-   **Python:** The primary programming language.
-   **TensorFlow:** An open-source machine learning framework.
-   **Keras:** A high-level neural networks API, running on top of TensorFlow.
-   **Jupyter Notebook:** For interactive development, code execution, and documentation.
-   **NumPy:** For numerical operations and array manipulation.
-   **Matplotlib:** For data visualization.
-   **MNIST Dataset:** The widely used dataset of handwritten digits.

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

-   **Python 3.x**
-   **pip** (Python package installer)

### Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/MemaroX/CV_FInalProject.git
    cd CV_FInalProject
    ```

2.  **Install dependencies:**
    It is highly recommended to use a virtual environment.
    ```bash
    # Create a virtual environment
    python -m venv venv
    # Activate the virtual environment
    # On Windows:
    .\venv\Scripts\activate
    # On macOS/Linux:
    source venv/bin/activate

    # Install required packages
    pip install -r requirements.txt
    ```

### Running the Project

1.  **Activate your virtual environment** (if you created one).
2.  **Launch Jupyter Notebook:**
    ```bash
    jupyter notebook notebooks/main.ipynb
    ```
3.  **Open `main.ipynb`:** Your web browser will open with the Jupyter Notebook interface. Click on `notebooks/main.ipynb` to open the project notebook.
4.  **Execute Cells:** Run the cells sequentially to see the data loading, model building, training, and evaluation process.

## Project Structure

```
./
├── notebooks/          # Contains the main Jupyter Notebook
│   └── main.ipynb
├── assets/
│   └── images/         # Example images of handwritten digits
│       ├── number 0.png
│       └── ...
├── docs/               # (Optional) Additional documentation or reports
├── LICENSE             # Project license
├── README.md           # This file
└── requirements.txt    # Python dependencies
```

## Examples

The `assets/images/number X.png` files are examples of the handwritten digits that the model is trained to recognize.

## Contributing

Contributions are welcome! If you have suggestions for improvements, bug fixes, or new features, please feel free to:

1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/YourFeatureName`).
3.  Make your changes.
4.  Commit your changes (`git commit -m 'Feat: Add YourFeature'`).
5.  Push to the branch (`git push origin feature/YourFeatureName`).
6.  Open a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

MemaroX - [Your GitHub Profile Link](https://github.com/MemaroX)
