# AI Agent Instructions for Data Collection Project

## Project Overview
This is a data analysis and collection project focused on importing and manipulating data from various sources using Python. The project is structured as a Jupyter Notebook-based educational resource.

## Key Components

### Main Notebook
- Primary file: `ImportacionDesdeDiversasFuentes.ipynb`
- Purpose: Demonstrates data import and analysis techniques using Python
- Key libraries: pandas, scikit-learn, os

### Data Directory
- Location: `/data`
- Contains various data files in different formats:
  - CSV files with different structures (e.g., `CSV_EX_1.csv`, `CSV_EX_blankline.csv`)
  - Text files (`Table_EX_1.txt`, `Table_tab_separated.txt`)
  - JSON data (`movies.json`)
  - Domain-specific datasets (`Boston_housing.csv`, `incendios-forestales.csv`)

## Development Patterns

### Data Loading Conventions
- Use pandas for data import operations
- Handle various file formats (CSV, TXT, JSON)
- Consider different data structures (blank lines, footers, headers)

### Data Analysis Workflow
1. Import required libraries (pandas, os)
2. Load data using appropriate pandas methods
3. Create DataFrame structures
4. Perform data visualization when applicable

## Environment Setup
Required Python packages:
- pandas: For data manipulation and analysis
- scikit-learn: For built-in datasets and machine learning capabilities
- matplotlib/seaborn: For data visualization

## Best Practices
- Always use pandas DataFrame for structured data manipulation
- Include markdown cells for documentation and explanations
- Follow the notebook's educational structure when adding new content
- Use descriptive variable names that reflect the data content

## Examples
```python
# Loading data example
import pandas as pd
df = pd.read_csv('data/CSV_EX_1.csv')

# Creating visualizations
df.plot.scatter(x='column1', y='column2')
```