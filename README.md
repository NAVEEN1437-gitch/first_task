
# 🧹 Data Cleaning & Preprocessing

- In this project, I worked with the Customer Personality Analysis (Marketing Campaign) dataset and performed several preprocessing steps to make the data clean, consistent, and ready for analysis.

# ✅ Steps Performed

### 1) Handling Missing Values

- Checked for null values using .isnull().sum().

- Filled missing numerical values (like Income) with the median to avoid skewness.

### 2) Removing Duplicates

- Detected duplicate rows using .duplicated().

- Removed them with .drop_duplicates() to ensure each customer is unique.

### 3) Standardizing Text Values

- Converted categorical/text columns (like Gender, Country) to a consistent format (lowercase, trimmed spaces).

- Renamed columns to uniform format (lowercase_with_underscores).

### 4) Converting Date Formats

- Standardized dt_customer column to proper datetime format (dd-mm-yyyy).

- Extracted useful features like year of joining.

### 5) Renaming Column Headers

- Renamed headers to be clean and consistent (e.g., Year_Birth → year_birth, Dt_Customer → dt_customer).

- Ensured no spaces, only lowercase with underscores.

### 5) Fixing Data Types

- Converted year_birth from datetime to integer year (1985, 1990, etc.).

- Converted Income from float to integer type.

- Ensured date columns (dt_customer) are stored as proper datetime objects.

# 📊 Outcome

After cleaning, the dataset is:

- Free from missing values (handled appropriately).

- Duplicate-free.

- Columns are well-structured, consistent, and easy to use.

- Data types are corrected (numeric where needed, datetime where applicable).

- This ensures the dataset is ready for analysis, visualization, and modeling.
