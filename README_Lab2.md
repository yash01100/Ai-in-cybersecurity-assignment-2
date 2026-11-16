# AI in Cyber Security – Lab Assignment 2

**Topic:** Detecting Suspicious Login Activity Using Machine Learning  
**Course:** ENSP355 | K.R. Mangalam University

## Files
- `AI_Cybersecurity_Lab2.ipynb` – executed Google Colab/Jupyter notebook with all six questions, code, outputs, tables and charts.
- `simple_login_activity.csv` – reproducible synthetic input dataset.
- `Lab2_Login_ML_Result.csv` – cleaned dataset with K-Means cluster labels.
- `confusion_matrix.png` – Decision Tree confusion matrix.
- `feature_importance.png` – Decision Tree feature importance chart.

## Important dataset note
The assignment PDF refers to `simple_login_activity.csv` and a starter notebook, but those files were not included with the uploaded PDF. This submission therefore generates a clearly labelled synthetic 100-record dataset (no real account or network data), inserts missing values and duplicate rows for the cleaning exercise, then cleans it as required.

## Run in Google Colab
1. Open https://colab.research.google.com/
2. Choose **File → Upload notebook** and select `AI_Cybersecurity_Lab2.ipynb`.
3. Choose **Runtime → Run all**.
4. Download the generated result CSV if needed.

## Results
- Cleaned dataset rows: 100
- Training rows: 75
- Testing rows: 25
- Decision Tree accuracy on this generated dataset: 84.00%

Results can vary if the synthetic data-generation code is changed. This is an educational demonstration, not a production security detector.
