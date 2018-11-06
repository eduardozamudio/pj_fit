# pj_fit
The aim of this repository is to apply Information Retrieval techniques to Person-Job Fit for selection of experts


## Data
 
This repository contains labeled data for the classification of *descriptions* containing demands and abilities in expert selection processes.

**data/OSTP_CHRH_senators_labeled.csv**

Data corresponds 65 nomination documents of Congressional Session Hearings (CSHR) of the Committee on Commerce, Science, and Transportation of the US Senate (CCST). Nominations took place from March 2000 to July 2013. We downloaded documents from the public repository of the Federal Digital System (FDsyshttp://www.gpo.gov/fdsysinfo/aboutfdsys.htm. Online in September 2018.), in plain text format, in November 2017. 

The dataset contains  7,738 sentences filtered from the 65 documents. Each sentence was manually labeled by domain experts as a nominee description (D - positive class) or no description (N - negative class).

The dataset has a skewed class distribution, with 1,001 positive class sentences and 6,737 negative class sentences.


The main features of the dataset include:

• data sources opened to public access
• data sources about nomination audiences for confirmation of candidates to cover executive positions in public service
• resulting dataset contains descriptions of the candidates under evaluation
• descriptions of candidates are expressed by the evaluators of the selection processes (senators)
