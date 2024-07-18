# Utilizing-machine-learning-for-attributing-sources-of-foodborn-pathogens-
# Introduction
Escherichia Coli (E. coli) is a leading cause of bacterial-derived foodborne disease, which significantly impacts human health worldwide [1]. It can spread through contaminated food and water. Source attribution may help to link human infections to food sources and animal reservoirs using whole genome sequencing (WGS) data [2].  This can improve the treatment of foodborne infections and aid public health interventions. Most current research on applying machine learning to pathogen source attribution surveillance mainly focuses on highly developed countries. However, some WGS datasets are available in public databases for low-resource countries and have not been fully exploited in developing machine-learning models that may aid in tracking foodborne pathogens. Therefore, this project aims to utilize the publicly available WGS dataset to Investigate the potential of applying machine learning to predict the host sources of E. coli from East African countries. Identify the SNPs and genes associated with the host source attribution for E. Coli.

# Objectives
- To develop a machine-learning model that may aid in tracking foodborne pathogens
- To Investigate the potential of applying machine learning to predict the host sources of E. coli from East African countries. 
- Identify the SNPs and genes associated with the host source attribution for E. Coli.
# Data
The data  that will e used from the study will be obtained from [NCBI isolate browser database](https://www.ncbi.nlm.nih.gov).

The dataset used in the study is in [pathogen folder](https://www.ncbi.nlm.nih.gov/pathogens/isolates)
# Steps to achieve the objectives of this project; 

- Acquire publicly available E. coli dataset from the NCBI pathogen genome browser (https://www.ncbi.nlm.nih.gov/pathogens/isolates). The metadata summary table from the pathogen genome browser will aid in identifying and filtering the E. coli with known host sources, country of origin, and their Biosmaple IDs that can be used to retrieve raw genomic sequences from the NCBI database. 
- Perform quality control 
- Perform variant calling using a reference genome such as Escherichia coli K-12 MG1655 [2] or other reference genomes supported by the literature. 
- Feature engineering and dimensionality reduction 
- Machine learning exploration: Train different machine learning models 
- Model interpretability: identify potential genomic variations (SNPs) associated with the host source attribution of E. coli.
# workflow
# Results
## Selected references 
- Lupolova, Nadejda, et al. "Patchy promiscuity: machine learning applied to predict the host specificity of Salmonella enterica and Escherichia coli." Microbial genomics 3.10 (2017): e000135.
- Blattner, Frederick R., et al. "The complete genome sequence of Escherichia coli K-12." science 277.5331 (1997): 1453-1462.


# Contributors
1. Doreen Kinya [Github](https://github.com/users/DOREENKDAVID)
2. Kimani Kariuki [Github](https://github.com/Kimani-kj)
3. Isaya Odongo [Github](https://github.com/users/OdongoIsaya)
4. Parcelli Jepchirchir [Github](https://github.com/users/Parcelli)
5. Joel Alukwe [Github](https://github.com/users/JoelALukwe)
