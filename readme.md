This project analyzes commercial flight delays using Python. It explores the dataset, visualizes delay causes, and builds simple models to identify major contributors to flight delays. The dataset is downloaded from Kaggle through `kagglehub`.

## Project Structure

```
.
├── flight-delay.ipynb      # Jupyter notebook for analysis
├── requirements.txt        # Python dependencies
└── data/                   # Optional folder for local sample data
```

Although a small sample dataset is included for demonstration, the notebook primarily imports the real dataset from Kaggle.

## Data Source

The dataset is automatically pulled from Kaggle.

## Setup Instructions

Use Python 3.9 or later.

```bash
python3 -m venv venv
source venv/bin/activate       # On Windows: venv\\Scripts\\activate
pip install --upgrade pip
pip install -r requirements.txt
```

### Main Dependencies

- numpy, pandas – for data handling
- matplotlib, seaborn – for visualization
- scikit-learn – for preprocessing and modeling
- kagglehub – for downloading data from Kaggle
- IPython – for notebook utilities

## Running the Notebook

1. Activate the virtual environment.
2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open `flight-delay.ipynb` and run the cells in order.

The notebook will automatically download the dataset from Kaggle. A small embedded dataset is available for quick testing if Kaggle is not configured.

## Notes

- `os`, `math`, and `datetime` are built-in Python modules and should not be listed in `requirements.txt`.
- `mpl_toolkits` is included with `matplotlib`.
- Always upgrade `pip` before installing dependencies to avoid version issues.

## License

This project is released under the MIT License.
You are free to use, modify, and distribute the code with proper attribution.

## Acknowledgments

- Kaggle for providing the dataset
- The NumPy, Pandas, Matplotlib, Seaborn, scikit-learn, DuckDB, and KaggleHub communities for their open-source tools
