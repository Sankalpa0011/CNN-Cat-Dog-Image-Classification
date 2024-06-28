---

# Cat-Dog Image Classification
---

This repository contains code for classifying images of cats and dogs using Convolutional Neural Networks (CNNs). Two approaches are demonstrated: building a custom CNN from scratch and using the MobileNet architecture for transfer learning.

## Dataset

The dataset used for this project is from Microsoft and can be downloaded [here](https://www.microsoft.com/en-us/download/confirmation.aspx?id=54765).

## Project Structure

- `01 CNN Cat-Dog Image Classification ( Dataset Creation ).ipynb`: Notebook for creating the dataset.
- `01 MobileNet CNN Cat-Dog Image Classification ( Dataset Creation ) Transfer Learning.ipynb`: Notebook for creating the dataset specifically for MobileNet.
- `02 CNN for Cat-Dog Image Classification ( Train The Neural Network ).ipynb`: Notebook for training a custom CNN.
- `02 MobileNet CNN Cat-Dog Image Classification ( Train The Neural Network ) Transfer Learning.ipynb`: Notebook for training a MobileNet CNN using transfer learning.

## Requirements

- Python 3.x
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Jupyter Notebook

You can install the required packages using the following command:

```bash
pip install tensorflow keras numpy matplotlib jupyter
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/yourusername/cat-dog-classification.git
cd cat-dog-classification
```

2. Download the dataset from the link provided and extract it to a directory named `dataset`.

3. Open the Jupyter notebooks in your preferred environment:

```bash
jupyter notebook
```

4. Run the notebooks in the following order:

   - `01 CNN Cat-Dog Image Classification ( Dataset Creation ).ipynb`
   - `01 MobileNet CNN Cat-Dog Image Classification ( Dataset Creation ) Transfer Learning.ipynb`
   - `02 CNN for Cat-Dog Image Classification ( Train The Neural Network ).ipynb`
   - `02 MobileNet CNN Cat-Dog Image Classification ( Train The Neural Network ) Transfer Learning.ipynb`

## Results

The notebooks will demonstrate the process of training and evaluating the models, and the results will be displayed within the notebooks.

---
