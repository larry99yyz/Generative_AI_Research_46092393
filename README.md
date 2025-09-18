# Generative AI Research Project

This repository contains all data, scripts, and documents for the research project "Generative AI".

## Project Structure

The repository is organized as follows:

```
Generative_AI_Research_SID/
├── literature_review/       # Journal articles, conference papers, books
├── data_analysis       # whole data analysis document
│   ├── quantitative_analysis/   # Survey data, analysis scripts (Python), reports
│   └── qualitative_analysis/    # Interview transcripts, protocols, consent forms
├── reports/      # the whole reports document
│   ├── proposal/   # The project proposal
|   ├── final_report.md   # finial report
│   └── history/    # The history draft 
├── additional_materials/    # Information sheets, photos, and media
└── README.md                   # This file
```

## Data Notes

*   **Sensitive Data**: The `03_qualitative_analysis/` directory contains sensitive information (e.g., interview transcripts, consent forms). Handle this data with strict confidentiality.
*   **Raw Data**: Raw data is stored in `02_quantitative_analysis/data/raw/` and should be considered read-only. All data cleaning and transformation should be done in scripts, outputting to the `cleaned/` directory.

## Usage

To run the quantitative analysis:
1.  Navigate to the `02_quantitative_analysis/scripts/` directory.
2.  Run the Python scripts in order (e.g., `1_data_cleaning.py` then `2_data_analysis.py`).

## Contributing

Contributors are welcome to fork this repository and submit pull requests. Please follow this workflow:
1.  Create a feature branch (`git checkout -b feature/NewFeature`).
2.  Commit your changes (`git commit -m 'Add some NewFeature'`).
3.  Push to the branch (`git push origin feature/NewFeature`).
4.  Open a Pull Request for review.
