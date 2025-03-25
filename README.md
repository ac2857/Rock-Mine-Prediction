

# Rock vs Mine prediction Model

A lightweight machine learning project that uses a predictive model to determine whether the object is a rock or a mine.


## Table of Contents
- [Project Structure]
- [Getting Started]
- [Dependencies]
- [Usage]
- [Project Details]

## Project Structure

```
.
├── sonar_data.csv
├── Prediction.ipynb
└── README.md
```


## Getting Started

These instructions will help you set up your environment to run the notebook locally.

1. **Clone or Download the Repository**  
   ```bash
   git clone https://github.com/ac2857/ROCK-MINE_PREDICTION.git
   cd ROCK-MINE-PREDICTION
   ```

2. **Set Up a Python Virtual Environment** (recommended)  
   ```bash
   python3 -m venv venv
   source venv/bin/activate  
   ```

3. **Install Dependencies**  
   `install the needed libraries manually (e.g., `pandas`, `numpy`, `scikit-learn`, etc.). Included in the code.

4. **Launch Jupyter Notebook**  
   ```bash
   jupyter notebook
   ```
   Then open `Prediction.ipynb` in your browser to explore and run the code cells.

## Dependencies

- **Python 3.7+**
- **Jupyter** (to run the notebook)
- Common data science libraries, such as:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `matplotlib`
  

## Usage

1. **Open the Notebook**:  
   Launch the Jupyter notebook server and open `Prediction.ipynb`.

2. **Run the Cells**:  
   Execute each code cell sequentially to:
   - Load and preprocess the data
   - Train and evaluate the model
   - Generate predictions or plots

3. **Modify/Experiment**:  
   - Adjust hyperparameters
   - Try different feature engineering steps
   - Explore alternative models or evaluation metrics

4. **Results**:  
   - Check model performance metrics printed in the notebook
   - Explore visualizations or predictions (e.g., classification reports, confusion matrices, etc.)

## Results

Accuracy on training data :  0.8342245989304813
Accuracy on test data :  0.7619047619047619

