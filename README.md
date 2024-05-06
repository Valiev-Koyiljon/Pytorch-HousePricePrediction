
# Boston Housing Price Prediction with PyTorch

This repository hosts a PyTorch implementation of a linear regression model aimed at predicting house prices using the Boston Housing dataset. This project is designed to showcase a basic machine learning workflow from data preparation to training and making predictions.

## Project Overview

The project utilizes the Boston Housing dataset, which is a well-known resource in machine learning circles. The model predicts the median value of owner-occupied homes based on various environmental and social factors.

### Features and Labels

The Boston Housing dataset includes the following features:
- **CRIM**: Per capita crime rate by town.
- **ZN**: Proportion of residential land zoned for lots over 25,000 sq.ft.
- **INDUS**: Proportion of non-retail business acres per town.
- **CHAS**: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise).
- **NOX**: Nitric oxides concentration (parts per 10 million).
- **RM**: Average number of rooms per dwelling.
- **AGE**: Proportion of owner-occupied units built prior to 1940.
- **DIS**: Weighted distances to five Boston employment centers.
- **RAD**: Index of accessibility to radial highways.
- **TAX**: Full-value property-tax rate per $10,000.
- **PTRATIO**: Pupil-teacher ratio by town.
- **B**: 1000(Bk - 0.63)^2 where Bk is the proportion of black residents by town.
- **LSTAT**: Percentage lower status of the population.
- **MEDV**: Median value of owner-occupied homes in $1000's (the target variable).

## Installation and Usage

### Clone the Repository

```bash
git clone https://github.com/Valiev-Koyiljon/Pytorch-HousePricePrediction.git
cd Pytorch-HousePricePrediction
```

### Install Dependencies

Ensure you have Python 3.8+ and pip installed, then run:

```bash
pip install -r requirements.txt
```

### Run the Notebook

Open the Jupyter Notebook to view the project:

```bash
jupyter notebook HousePricePredictionWithPytorch.ipynb
```

Follow the instructions within the notebook to train the model and make predictions.

## Model Architecture

The model uses a simple linear regression structure provided by PyTorch's `nn` module, with an input size corresponding to the number of features (13) and an output size of 1.

## Results

The training process and the model's predictions can be examined in detail in the `HousePricePredictionWithPytorch.ipynb` notebook.

## Contributions

Contributions are welcome! Please feel free to submit a pull request or open an issue if you have suggestions or find bugs.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE.md) file for details.
