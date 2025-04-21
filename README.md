# srd_exit_interview_analysis_kobotoolbox

## Directory Structure

```
data/
  raw/                  # Raw data files directly exported from KoBoToolbox
  cleaned/              # Cleaned datasets ready for analysis
notebooks/
  01-data-import.ipynb  # Notebook for importing data
  02-cleaning.ipynb     # Data cleaning steps
  03-analysis.ipynb     # Exploratory and statistical analysis
  04-report.ipynb       # Generating visual reports or summaries
reports/
  figures/              # Save plots, graphs, and charts
  summary_reports/      # Exported report files (PDF, Excel, etc.)
scripts/                # Python scripts for repeated use
  utils.py              # Helper functions
README.md               # Project description
requirements.txt        # List of required packages
.gitignore              # Files/folders to ignore in Git