# A systematic evidence map and bibliometric analysis of the behavioural impacts of pesticide exposure on zebrafish.

## Cite the data and code as: 

The repository described below contains the data, bibliometric files, and code used for this study. A pre-compiled file is also provided:

Please find the detailed description of the folders and their content below. Should you wish to reuse any data or analysis for future studies, kindly contact Kyle Morrison at kyle.morrison@unsw.edu.au.

## literature_search 
This folder contains all the bibliometric files created during the literature search. This folder contains the following four sub folders
- zf_sm_literature_database_search: Contains bibliographic files from literature database searches.
- zf_sm_grey_literature_search: Includes bibliographic files from grey literature searches.
- zf_sm_backward_forward_search: Stores bibliographic files from backward and forward citation searches.
- zf_sm_all_search_combined: Houses all search files combined, together with an R code for duplicate removal.

### zf_sm_literature_database_search 
- zf_sm_search_scopus.bib: Bibliographic file with results from the Scopus literature search.
- zf_sm_search_wos.bib: Bibliographic file with results from the Web of Science literature search.
- zf_sm_search_pubmed.bib: Bibliographic file with results from the PubMed literature search.
- zf_sm_search_pubmed_mesh.bib: Bibliographic file with results from the PubMed literature search using MeSH terms.

### zf_sm_grey_literature_search
The grey literature search was conducted on the Bielefeld Academic Search Engine (BASE). Files in this directory contain:
- zf_sm_grey_search_base1.bib: Bibliographic file containing the first 10 studies retrieved from BASE.
- zf_sm_grey_search_base2.bib: Bibliographic file containing studies 11-20 retrieved from BASE.
- zf_sm_grey_search_base3.bib: Bibliographic file containing studies 21-30 retrieved from BASE.
- zf_sm_grey_search_base4.bib: Bibliographic file containing studies 31-40 retrieved from BASE.
- zf_sm_grey_search_base5.bib: Bibliographic file containing studies 41-43 retrieved from BASE.

###  zf_sm_backward_forward_search
This subdirectory contains bibliographic files with studies that cite specific works, including:
- zf_sm_search_horzmann_backward.csv: Contains all studies citing Horzmann and Freedman, 2018 at the time of search.
- zf_sm_search_rennekamp_backward.csv: Contains all studies citing Rennekamp and Peterson, 2015 at the time of search.
- zf_sm_search_saiki_backward.csv: Contains all studies citing Saiki et al., 2021 at the time of search.
- zf_sm_search_tao_backward.csv: Contains all studies citing Tao et al., 2022 at the time of search.
- zf_sm_search_combined_forward.csv: Contains all studies that the above-cited studies reference.

## literature_screen
This directory houses bibliographic files used for title, abstract, and keyword screening, along with full-text screening:
- zf_sm_abstract_screening.csv: bibliographic file containing all studies for title, abstract and keyword screening.
- zf_sm_full_text_screening.csv: bibliographic file containing all studies for full-text screening. 

## data
This directory encompasses all the data procured during the data extraction phase. It comprises the following files:
- zf_sm_behaviour_details.csv: This file contains all the extracted data regarding zebrafish behavior.
- zf_sm_bibliometrics.csv: This file contains all the extracted bibliometric data.
- zf_sm_pesticide_details.csv: This file contains all the extracted data on the pesticides used.
- zf_sm_pesticide_dosage.csv: This file contains all the extracted data on the pesticide characteristics used in the study design.
- zf_sm_study_details.csv: This file contains all the extracted data regarding the zebrafish characteristics used in the study design.
- scopus.bib: This bibliometric file includes all studies incorporated into the map for bibliometric analysis.

## R
This directory includes R code, markdown, and associated files. It contains the following:
- zf_sm_code_cache: This is the cache produced from knitting the Rmarkdown.
- zf_sm_code_files: These are files generated from knitting the Rmarkdown.
- zf_sm_code.html: This is the knitted analysis code.
- zf_sm_code.rmd: This is the raw analysis code.

## figures
This directory stores all the created figures in both PDF and JPEG formats.
