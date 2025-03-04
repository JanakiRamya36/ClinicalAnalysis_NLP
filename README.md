# Enhancing Clinical Analysis using NLP

## Project Overview  
This project leverages Natural Language Processing (NLP) techniques to analyze 398 medical discharge summaries from the DBMI Data Portal of Harvard Medical School. 
The primary objectives were:  
1. Classifying smoking status using Naive Bayes models trained on unigram, bigram, and trigram features.  
2. Extracting and analyzing ALP (Alkaline Phosphatase) values and bone mentions using Named Entity Recognition (NER).  
3. Exploring relations between ALP and bone mentions to determine potential clinical correlations.  

## Data Analysis 
- **Smoking Status Classification:**  
  - Implemented Naive Bayes classifiers with unigram, bigram, and trigram models.  
  - Achieved 65% accuracy with a bigram-based classifier, significantly improving over unigram (20%) and trigram (6%).  
- **Named Entity Recognition (NER):**  
  - Successfully extracted ALP values and bone mentions from medical text using spaCy.  
  - Achieved 70% accuracy (7 out of 10 instances) in extracting ALP values. 
- **Relation Extraction (RE):**  
  - Attempted to identify direct associations between ALP and bone health but found all extracted relations to be false due to syntactic complexity and contextual variations in medical records.   
 
## Tools Used  
- **Programming Language:** Python  
- **Libraries:** spaCy, Scikit-learn, NLTK, Pandas, NumPy, Matplotlib

## Repository Structure  
- **`Project_NER_and_RE.ipynb`** – Jupyter Notebook for Named Entity Recognition (NER) and Relation Extraction (RE)  
- **`Project_Text_classification.ipynb`** – Jupyter Notebook for Smoking Status Text Classification  
- **`smoking dataset.csv`** – Clinical text dataset used for analysis  
- **`ClinicalAnalysis_NLP.pptx`** – Presentation summarizing findings  
- **`ClinicalAnalysis_NLP@article.docx`** – Detailed report on the project  
- **`README.md`** – Project documentation

## Author information
Janaki Ramya Namburu\
email: janakiramyan@gmail.com\
LinkedIn: www.linkedin.com/in/janakiramya

