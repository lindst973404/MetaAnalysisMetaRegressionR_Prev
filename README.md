# Meta-Analysis and Meta-Regression using R

This project intends to demonstrate how to conduct a meta-analysis and 
meta-regression using current R packages with the focus on estimating prevalence.


## What's Included

- **Notebook**: `MetaAnalysisR_PrevalencePrEPawareness.Rmd`  

- **PDF output**: `MetaAnalysisR_PrevalencePrEPawareness.pdf`  

- **Dummy Data from data extraction**: `data_extract.RData`  
  

## Additional Modifications

- Manual control over table titles and numbering (no auto-numbering)
- Float-resistant LaTeX tables using `longtable` and raw LaTeX blocks
- Data manipulation for one predictor for meta-regression exercise
- Clean, reproducible RMarkdown-to-PDF pipeline using `pdflatex`

## How to Reproduce

To regenerate the notebook and PDF:

1. Clone the repository
2. Open `MetaAnalysisR_PrevalencePrEPawareness.Rmd` in RStudio
3. Ensure the data file `data_extract.RData` is located where desired   
4. Knit to HTML using the Knit button or `rmarkdown::render()`

> Note: This notebook is designed for manual control over table layout and numbering. Auto-numbering and float environments are intentionally disabled.

## Author

**Lindsay Trujillo, PhD, MPH**  
Senior Data Scientist & Epidemiologist  
Specializing in reproducible analytics, regulatory documentation, and 
data simulation for advanced training and generating insights for 
clear stakeholder-ready reporting.

### Suggested Citation

Trujillo L. *Meta-Analysis and Meta-Regression using R*. GitHub. October 2025.

## License

This project is released under the MIT License. See `LICENSE` for details.
