# Derma-AI: Skin Cancer Classification

![License](https://img.shields.io/badge/license-MIT-blue.svg)

This project aims to classify skin lesions as benign or malignant using a deep learning model. The provided Jupyter Notebook (`abhinav_1.ipynb`) contains the code for data preprocessing, model training, and evaluation.

## Dataset

The model is trained on the **Skin Cancer MNIST: HAM10000** dataset. This dataset contains 10,000 training images of skin lesions, categorized into seven different classes.

For more information about the dataset, you can visit the Kaggle dataset page: [https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000](https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000)

## Getting Started

### Prerequisites

*   Python 3.x
*   Jupyter Notebook or JupyterLab
*   The required Python libraries, which can be installed via pip:
    ```bash
    pip install matplotlib numpy pandas pillow
    ```

### Running the Notebook

1.  Clone this repository:
    ```bash
    git clone https://github.com/Abhinavmehra2004/dermascan.git
    ```
2.  Navigate to the cloned directory:
    ```bash
    cd dermascan
    ```
3.  Start Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
4.  Open `abhinav_1.ipynb` and run the cells.

## Usage

The notebook is divided into several sections:

1.  **Data Loading and Preprocessing**: Loads the dataset, and prepares it for training.
2.  **Data Augmentation**: Augments the data to increase the size of the training set and prevent overfitting.
3.  **Model Building**: Defines the architecture of the deep learning model.
4.  **Training**: Trains the model on the preprocessed data.
5.  **Evaluation**: Evaluates the performance of the trained model.

## Results

The notebook will output the performance of the model, including accuracy and loss metrics. The goal is to achieve a high accuracy in classifying skin lesions, which can aid in the early detection of skin cancer.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue if you have any suggestions or find any bugs.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
