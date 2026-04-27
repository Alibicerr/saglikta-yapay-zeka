# Smart Health Assistant

This project is a small YMH220 course project. The idea is simple: use patient symptoms to estimate the most likely disease and give the doctor a second check. The main focus here is data exploration and a small baseline model.

## Project Files

- `disease_symptoms_eda_colab.ipynb` is the main notebook for this project.
- `data_preparation_colab.ipynb` prepares the raw file and saves the split files.
- `disease_distribution_colab.ipynb` checks disease balance.
- `symptom_patterns_colab.ipynb` looks at symptom counts and common symptoms.
- `baseline_model_colab.ipynb` runs the simple baseline model.
- `data/raw/disease_symptoms_raw.csv` is the combined raw dataset.
- `data/Training.csv` and `data/Testing.csv` are the split files created from the raw data.

## What the Notebook Does

- Loads the raw symptoms dataset.
- Splits the raw data into training and test sets.
- Uses unique symptom patterns for the split to avoid leakage between train and test.
- Saves the split files into the `data` folder.
- Checks class balance and common symptoms.
- Counts how many symptoms appear in each row.
- Trains a small baseline model for a quick test.

## How to Run

1. Open `disease_symptoms_eda_colab.ipynb` in Google Colab.
2. Upload `disease_symptoms_raw.csv` to the Colab file area.
3. Run the cells from top to bottom.

## Note

This is a course demo, not a medical product. The results are for learning and basic analysis.
