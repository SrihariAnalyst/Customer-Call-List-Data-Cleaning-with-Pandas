📖 Overview
This project demonstrates how to clean and prepare a Customer Call List dataset using Python (Pandas).
The dataset initially contained:
- Inconsistent phone number formats
- Missing values in names, addresses, and contact fields
- Duplicate records (e.g., Anakin Skywalker appearing twice)
- Extra/unnecessary columns
Through systematic cleaning, the dataset was transformed into a structured, reliable format ready for analysis.

📂 Repository Contents
- customer_call_list_raw.xlsx → Original dataset (uncleaned)
- customer_call_list_cleaned.xlsx → Final cleaned dataset
- customer_call_list_cleaned.csv → Cleaned dataset in CSV format
- data_cleaning.ipynb → Jupyter Notebook with step‑by‑step cleaning code
- README.md → Project documentation

⚙️ Requirements
- Python 3.x
- Pandas
- Jupyter Notebook

🧹 Cleaning Steps
- Standardized phone number formats
- Normalized “Paying Customer” and “Do Not Contact” values (Yes/No)
- Removed duplicates
- Dropped unnecessary columns (Not_Useful_Column)
- Handled missing values consistently

📊 Example Output
The cleaned dataset now includes:
- Consistent phone numbers (e.g., 123-545-5421)
- Clear customer status fields (Yes / No)
- No duplicate records
- Only relevant columns retained

🔑 Key Takeaways
- Data Cleaning Expertise → Applied Pandas techniques to standardize formats, handle missing values, and remove duplicates.
- Attention to Detail → Identified inconsistencies in names, phone numbers, and customer status fields, ensuring accuracy.
- Reproducible Workflow → Documented each cleaning step in a Jupyter Notebook for transparency and repeatability.
- Practical Application → Transformed a messy customer call list into a structured dataset ready for analysis and reporting.
- Recruiter‑Friendly Portfolio → Showcases ability to work with real‑world messy data, a core skill for data analyst roles
