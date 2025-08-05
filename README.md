# **Embryos are largely understudied in conservation physiology**

This repository contains the data and code to reproduce the results from Pottier *et al.* (2025). Embryos are largely understudied in conservation physiology. 

Note that a knitted version of the code is available (`index.html`). This rendered version is easy to navigate and produces all the outputs. 

This repository is managed by Patrice Pottier (p.pottier@unsw.edu.au). Please feel free to contact Patrice if you have any questions or find a mistake in the code. 

---

Below is an overview of the folder structure and contents of this repository: 

## **Bibliographic_searches** 

This folder contains all the bibliographic files used to synthesise the evidence. 

* *bib_format*: folder containing files extracted from each journal in bibtex format.

* *excel_format*: folder containing files extracted from each journal in csv format.

* *all_bibliographic_records.bib*:  bibliographic files extracted from all journals (bitex format).

* *all_bibliographic_records.csv*:  bibliographic files extracted from all journals (csv format).

* *all_included_studies.csv*: file containing the citation information for all studies that were included in the study.

## **Data**

This folder contains the raw data extracted from each individual study using Google Forms.

* *extracted_data_cons_phys_life_stages.csv*: extracted data in csv format.

* *extracted_data_cons_phys_life_stages.csv*: extracted data in excel format.

* *cleaned_data.csv*: cleaned dataset after fixing typologies and standardising data collection (see code for details).

## **Fig** 

This folder contans the figures used for the publication. Note that all figures underwent cosmetic adjustments in Illustrator. 

## **R** 

This folder contains the R files used to process the data for this study. 

* *bibliography_processing.Rmd*: file detailed the steps used to combine bibliographic files from different journals and separate them among co-authors for screening and extraction.

* *data_processing_and_visualisation.Rmd*: file detailing the steps of data curation, calculation of descriptive statistics, and figure creation. 

* *data_processing_and_visualisation.html*: same file as above, but rendered through Rmarkdown. 

## **Screening** 

This folder contains the files used to screen articles for eligibility

* *Studies_to_screen* : folder containing subsets of bibliographic records distributed among co-authors for screening.

* *Decision_tree_cons_phys_life_stages.pptx*: decision tree used to screen studies for eligibility. 

