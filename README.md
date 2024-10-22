# Fish-Weight-Prediction🐟

Fish Weight Prediction is a machine learning project that estimates the weight of fish based on various features like length, height, and species. The repository includes data preprocessing, exploratory analysis, and model training using regression techniques in Python.

## Table of Contents

- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Model](#model)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Dataset

The dataset used for this project contains the following features:
- **Species**: The species of the fish.
- **Length1**: Vertical length in cm.
- **Length2**: Diagonal length in cm.
- **Length3**: Cross length in cm.
- **Height**: Height of the fish in cm.
- **Width**: Diagonal width in cm.
- **Weight**: The weight of the fish (target variable).

## Project Structure


```bash
├── notebooks/          # Jupyter notebooks for EDA and model development
├── models/             # Trained models
├── src/                # Source code for data processing and modeling
├── results/            # Evaluation results and plots
├── README.md           # Project documentation
```

## Model
The model used for prediction is a regression model, specifically:

Linear Regression
Polynomial Regression
Decision Tree Regressor
The models were trained and evaluated using scikit-learn.

## Results
The model achieved a mean absolute error (MAE) of 50.6 and an R-squared value of 95.5% on the test set.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for improvements or bug fixes.

## License
This project is licensed under the Apache License. See the [LICENSE](LICENSE) file for details.
