# Smart Health Assistant

This project is a small YMH220 course project. The idea is simple: use patient symptoms to estimate the most likely disease and give the doctor a second check. The main focus here is data exploration and a small baseline model.

## Project Files

- `disease_symptoms_eda_colab.ipynb` is the main notebook for this project.
- `datasets/Training.csv` and `datasets/Testing.csv` are the dataset files.
- `diabetes_eda_colab.ipynb` is an earlier notebook from the first dataset choice.

## What the Notebook Does

- Loads the symptoms dataset.
- Cleans the extra empty column in `Training.csv`.
- Checks class balance and common symptoms.
- Counts how many symptoms appear in each row.
- Trains a small baseline model for a quick test.

## How to Run

1. Open `disease_symptoms_eda_colab.ipynb` in Google Colab.
2. Upload `Training.csv` and `Testing.csv` to the Colab file area.
3. Run the cells from top to bottom.

## Note

This is a course demo, not a medical product. The results are for learning and basic analysis.
