# Student Performance Prediction

This project predicts students' final exam scores based on their study hours and previous scores using a Random Forest Regressor model.

## Dataset
- **StudentID**: Unique ID for each student.
- **StudyHours**: Number of hours spent studying.
- **PreviousScores**: Scores from previous exams.
- **FinalExamScore**: Target variable (actual final exam score).

## Features
- Data preprocessing (handling missing values, encoding categorical data, feature scaling).
- Train-test split (80-20 ratio).
- Machine learning model: **Random Forest Regressor**.
- Model evaluation using MAE, MSE, and R² Score.
- Visualizations: actual vs predicted scores, residuals distribution, feature importance.

## Installation & Usage
Run the Jupyter Notebook in Google Colab:

1. Clone this repository:
2. Open Google Colab and upload `Student_Performance.ipynb`.
3. Upload the dataset when prompted.
4. Run all cells to train and evaluate the model.

## Results
- **Performance Metrics**: Evaluates the model’s accuracy.
- **Visualizations**: Helps in understanding predictions and errors.

## Files
- `Student_Performance.ipynb` - Jupyter Notebook with the complete code.
- `student_data.csv` - Sample dataset.
- `Student_Perf_Report.pdf` - Detailed report on the project.
- `README.md` - Project documentation.

## References
- Scikit-learn documentation
- Seaborn & Matplotlib for data visualization
- Dataset (Generated/Provided by instructor)

---
**Author**: Shashank Singh  
**License**: MIT  
