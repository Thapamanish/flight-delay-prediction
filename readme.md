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

The dataset is automatically pulled from Kaggle. To enable Kaggle access:

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

## Output

Processed and scaled datasets are saved in the project directory, for example as `positive_scaled_flight_delays.csv`.

If you see an error like:

```
OSError: Cannot save file into a non-existent directory
```

change the output path in the notebook to a valid local folder.

## Notes

- `os`, `math`, and `datetime` are built-in Python modules and should not be listed in `requirements.txt`.
- `mpl_toolkits` is included with `matplotlib`.
- Always upgrade `pip` before installing dependencies to avoid version issues.

## License

Add your preferred license here (e.g., MIT or Apache 2.0).

## Acknowledgments

- Kaggle for hosting the dataset
- NumPy, Pandas, Matplotlib, Seaborn, scikit-learn, and KaggleHub communities
  """

path_plain = "/mnt/data/README_plain_flight_delay.md"
with open(path_plain, "w", encoding="utf-8") as f:
f.write(plain_readme)

path_plain
