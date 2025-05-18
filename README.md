# Circuit Power Estimation using ANN and RNN

This project focuses on estimating power requirements of electronic circuits based on their parameters using machine learning models — specifically Artificial Neural Networks (ANN) and Recurrent Neural Networks (RNN).

## 📁 Files

- `new and final.ipynb`: Jupyter Notebook containing code for data preprocessing, model building, training, and evaluation.
- `circuit_parameters_vs_power (2).csv`: Dataset with circuit parameters and corresponding power values (used for training/testing).
- `circuit_power_data.csv`: Dataset containing predicted power outputs from the trained models.

## 🧠 Project Features

- **Data Preprocessing**: Normalization and transformation of raw circuit parameter data.
- **Modeling**:
  - **ANN (Artificial Neural Network)**: Learns nonlinear relationships between circuit parameters and power.
  - **RNN (Recurrent Neural Network)**: Explores any temporal dependencies in the data.
- **Evaluation**: Compares model performance using loss metrics and visualization plots.

## 🛠 Requirements

To run this project, make sure the following Python libraries are installed:

```bash
pip install numpy pandas matplotlib scikit-learn tensorflow
```

## 🚀 How to Run

1. Download or clone this repository.
2. Place all CSV files in the same directory as the notebook.
3. Open `new and final.ipynb` using Jupyter Notebook, VS Code, or Google Colab.
4. Run all cells in order to preprocess the data, train models, and evaluate performance.

## 📊 Output

- Trained ANN and RNN models for power estimation.
- Loss curves and performance metrics (e.g., MSE).
- CSV export of predicted vs actual power outputs.

## 📃 License

This project is licensed under the MIT License.

## 🙌 Acknowledgments

This work was done as part of a project to apply machine learning techniques in electronic circuit analysis and power prediction.
