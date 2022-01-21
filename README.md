# Msc-Thesis-Data-Science

## Weakly-Supervised Fine-Grained Semantic Indexing of Biomedical Literature using Citations

### 1. Motivation
A considerable part of the immense amount of biomedical data, available nowadays, consists of plain text, such as explanations of clinical trials, electronic health records, information on adverse events and research publications. Such texts are written in scientific language, including definitions, expressions and terms, necessitating the creation of a terminology to formalize and catalog these scientific terms
and concepts. The required terminology is also essential for the process of Information Retrieval (IR), for example when indexing publications or making queries on the text. Therefore, since the assignment of excerpting terms of a domain, by hand,is time and cost consuming, researchers focus in designing automated methods to aid know-how professionals to catalog the terms and concepts of a domain in the form of a vocabulary and automatically annotate biomedical publications. This allows users to retrieve information from a vast amount of biomedical text data efficiently and effortlessly using semantic search.

Most often the assigned tags are broad concepts, which describe the general notion of the biomedical terms, leaving out the more fine-grained concepts. This leads to the nonexistence of an indexing with such a granularity to facilitate scientists to explore more specific regions of biomedical literature. This tremendously affects the branch of diseases, in which narrower concepts very often depicts different types of a disease. The scientific community would benefit from an automated fine-grained partitioning of the related literature as it can efficiently reveal variations between the types of patients and provide accurate information for medicine applications.

This thesis belongs in the aforementioned field of biomedical semantic indexing,and specifically the annotation of biomedical text data with fine-grained scientific concepts. We are specifically interested in scientific literature annotation, thus indexing of biomedical research publications. Publication indexing is a significant part of knowledge extraction: researchers publish their work and results, which can be studied by others, to gain knowledge of work on a specific field. Fine-grainedindexing will provide more specialised search results, saving researchers’ time and effort.

### 2. Purpose and Research Questions
The goal of this thesis is to attempt to exploit the semantic information provided by all articles that cite or are cited by a piece of biomedical literature to accomplish its fine-grained semantic indexing with the relevant narrower concepts of a MeSH descriptor. To this end, the preliminary work on fine-grained semantic indexing, based on weak supervision [1] is further extended, to make use of such information
and the system is being tested on the case of Alzheimer’s Disease.

The research questions, this thesis attempts to address, are the following:

• Are the semantic features of citations and references being selected in the top
features for training of the models? Are they considered significant?

• Do the above semantic features help in the classification?

• Can the combination of both citations’ and references’ features make a differ-
ence to the performance of the classifiers?

### 3. Scope and Limitations
This study focuses on the effect of the semantic information, provided by cited and referenced papers, on the performance of machine learning classification algorithms. This piece of information is used to produce semantic features for the enrichment of the features of the training dataset and not as labels.

### 4. Target group
The work of this thesis can be beneficial to several types of members of the scientific community, including those involved in automated biomedical semanticindexing, those in need to extract literature under terms of fine granularity level and those in research of the effect of semantic features of citations and references on a fine-grained biomedical indexing method.

### For How to use, Licences and other please refer to:
[1] https://github.com/tasosnent/BeyondMeSH

## Reference

Nentidis, A., Krithara, A., Tsoumakas, G., & Paliouras, G. (2019). Beyond MeSH: Fine-Grained Semantic Indexing of Biomedical Literature Based on Weak Supervision. In 2019 IEEE 32nd International Symposium on Computer-Based Medical Systems (CBMS) (pp. 180–185). IEEE. https://doi.org/10.1109/CBMS.2019.00045
