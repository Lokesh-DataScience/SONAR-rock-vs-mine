# SONAR-rock-vs-mine

## Project Overview

SONAR-rock-vs-mine is a Machine Learning model that can classify between rocks and mines in deep sea using redar frequencies.

## Repository Contents

- **Dataset**: Sonar frequencies data points in CSV file .
- **rock-vs-mine-prediction.ipynb** : Jupyter notebook where the model has been trained on `Dataset`.
- **lr_model.pkl** : Machine learning model created in `rock-vs-mine-prediction.ipynb` notebook.
- **requirements.txt**: List of Python libraries required to run `rock-vs-mine-prediction.ipynb`.

## Getting Started

### Prerequisites

Ensure you have the following installed:
- Python 3.12
- pip

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Lokesh-DataScience/SONAR-rock-vs-mine.git
    cd SONAR-rock-vs-mine
    ```

2. Install the required Python libraries:
    ```bash
    pip install -r requirements.txt
    ```

### Running the Demo

You can check the last shell of `rock-vs-mine-prediction.ipynb` notebook to try with new data points:

### Usage
- **The rock-vs-mine-prediction.ipynb opens a notebook displaying the interface of jupyter.**
- **The model will take input from user as array and gives related and relevant classification either Rock or Mine.**
- 
### Model Details
- **The Scikit-learn is used for model building.**
- **This model is build to get classification between rock and mine as per user frequncy.**

### Contributing
- **Contributions are welcome! Please feel free to submit a Pull Request.**

### Acknowledgements
- **Jupyter for providing the tools for user interaction.**
- **Scikit-learn for the model training.**

