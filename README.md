# Testline_Assignment

# Quiz Performance Analysis

This project analyzes quiz performance data to generate recommendations, insights, and visualizations. It uses historical quiz data, submission data, and quiz metadata to provide a student-centric analysis. Below is an overview of the project's objectives, approach, and implementation.

---

## **Project Overview**

This project is designed to process quiz data, analyze performance trends, and generate actionable recommendations for students. It achieves the following:

- Summarizes historical performance with aggregated metrics.
- Identifies areas for improvement and trends in student performance.
- Provides personalized recommendations based on accuracy and correctness.
- Generates a student persona highlighting strengths and weaknesses.
- Outputs the processed data and recommendations to CSV files for further use.

---

## **Approach Description**

### **Data Sources**
- **Quiz Data:** Contains metadata about quizzes (e.g., topics, question types).
- **Submission Data:** Tracks individual quiz attempts with scores, accuracy, and answers.
- **Historical Data:** Provides a record of past quiz performance for analysis.

### **Key Functions**
1. **`analyze_submission_performance`**:
   - Aggregates submission-level metrics such as total score, average accuracy, and answer counts.

2. **`analyze_historical_performance`**:
   - Calculates summary statistics for scores, including average, max, and min.

3. **`analyze_performance_by_topic`**:
   - Groups historical data by quiz topic, computing metrics like average score and total attempts per topic.

4. **`generate_user_insights`**:
   - Identifies weak areas, improvement trends, and performance gaps based on average scores and accuracy thresholds.

5. **`create_recommendations`**:
   - Generates specific advice for each quiz based on accuracy and correctness.

6. **`define_student_persona`**:
   - Builds a profile of the student’s strengths and weaknesses and assigns a performance label.

### **Output**
- **CSV Files:**
  - `historical_performance_with_recommendations.csv`: Combines historical data with recommendations.
  - `recommendations.csv`: Contains standalone recommendations for readability.
  - `submissions.csv`
  - `historical_performance.csv'
- **Console Output:**
  - Summarized recommendations and insights for quick evaluation.

---

## **How to Run the Code**

### **Prerequisites**
1. Ensure you have access to Google Colab.
2. Upload the following JSON files to your Colab environment:
   - `quiz.json`
   - `submission.json`
   - `historical.json`

### **Steps**
1. **Load the Data:**
   - The provided code reads JSON files into Python dictionaries for analysis.

2. **Run the Analysis:**
   - Execute the notebook cells to process the data, analyze performance, and generate recommendations.

3. **Export Results:**
   - CSV files will be generated and saved for download, containing both historical performance data and recommendations.

---

## **Key Benefits**
- **Personalized Insights:** Tailored recommendations ensure students know where to focus.
- **Data-Driven:** Uses aggregated metrics and trends for evidence-based recommendations.
- **Scalable Design:** Modular functions make it easy to adapt to different datasets.

---

For any questions or further clarifications, feel free to reach out.
