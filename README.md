Company name : CODETECH IT Solutions 
Name : Shreya Akhilesh kumar singh 
INTERN ID : CT04Dh2687 
Domain : Python 
Duration : 4v week 
Mentor : Neela Santosh

📑 Automated Data Analysis PDF Report Generator
This Python script performs basic exploratory data analysis (EDA) on a given CSV file and generates a professional PDF report using the reportlab library.

🔹 Features
Reads and analyzes CSV datasets using Pandas.

Displays dataset shape, info, and descriptive statistics (mean, median, quartiles, min, max).

Checks for missing values and duplicate rows.

Cleans data by dropping null values.

Generates a styled PDF report containing:

File details (path, number of rows, columns)

Summary Statistics Table

Missing Values Table

📊 Example Workflow
Load CSV file → "Car_sales.csv"

Perform EDA → data.describe(), missing value checks, duplicates check

Clean data → Remove rows with NaN

Export results to PDF with formatted tables and headings

🛠 Requirements
bash
Copy
Edit
pip install pandas numpy matplotlib seaborn reportlab
🚀 Usage
Place your CSV file in the working directory.

Update the file_path variable with your CSV file location.

Run the script — it will generate Data_Analysis_Report.pdf.

📂 Output
A professional PDF report containing:

Title Page with dataset info

Summary Statistics Table (Mean, Std, Min, Max, Quartiles)

Missing Values Table with counts per column

