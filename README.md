# Train Route Analysis and Journey Time Prediction

## Project overview
This project analyzes train-route data and builds a Linear Regression model to estimate train journey duration.

The notebook covers:
- Loading and inspecting train-route data
- Basic data cleaning and preparation
- Train-wise journey summaries
- Exploratory data analysis and visualizations
- Training and evaluating a Linear Regression model
- Predicting journey duration from distance and number of stops

## Project files
- `Train_Route_Analysis.ipynb` — main Jupyter Notebook
- `Dataset1.csv` — input dataset required by the notebook (not included in this ZIP because it was not supplied with the notebook)
- `requirements.txt` — Python dependencies
- `.gitignore` — excludes common temporary and environment files

## Setup
1. Install Python 3.9 or later.
2. Open a terminal in this project folder.
3. Create and activate a virtual environment (optional but recommended):

   ```bash
   python -m venv .venv
   # Windows PowerShell
   .\.venv\Scripts\Activate.ps1
   ```
4. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
5. Place the dataset file named **`Dataset1.csv`** in the same folder as the notebook.
6. Start Jupyter:

   ```bash
   jupyter notebook
   ```

7. Open `Train_Route_Analysis.ipynb` and run the cells from top to bottom.

## Dataset note
The notebook currently loads the dataset using:

```python
df = pd.read_csv("Dataset1.csv")
```

Therefore, the file must be named exactly `Dataset1.csv` and placed beside the notebook. The dataset was not included in the uploaded materials, so add it before running the notebook. Check that you have permission to publish the dataset on GitHub; if it is large or restricted, keep it out of the repository and document where collaborators can obtain it.

## GitHub upload
Extract this ZIP, open the extracted folder in VS Code, and upload the project folder to your GitHub repository. Do not upload `.venv`, cache folders, or private data.
