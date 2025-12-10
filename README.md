# Enhancing Clinical Analysis Using NLP

## Project Overview
This project applies Natural Language Processing (NLP) techniques to 398 medical discharge summaries from the DBMI Data Portal (Harvard Medical School). The work focuses on three core tasks:

1. Classifying smoking status using Naive Bayes models with unigram, bigram, and trigram features.  
2. Extracting ALP (Alkaline Phosphatase) values and bone-related terms using Named Entity Recognition (NER).  
3. Exploring potential relationships between ALP values and bone mentions to understand whether text-based signals can assist in clinical interpretation.

## Data Analysis

### **Smoking Status Classification**
- Developed Naive Bayes models using unigram, bigram, and trigram representations.
- Performance:
  - **Bigram model:** ~65% accuracy  
  - **Unigram model:** ~20%  
  - **Trigram model:** ~6%
- The bigram model performed best, capturing more meaningful context compared to other feature sets.

### **Named Entity Recognition (NER)**
- Used spaCy to extract ALP values and bone-related entities from unstructured clinical text.
- ALP values were correctly extracted in **70% of cases** (7 out of 10 reviewed instances).
- The approach highlights both the potential and limitations of pattern-based NER in clinical notes.

### **Relation Extraction (RE)**
- Attempted to identify direct associations between ALP values and bone mentions.
- No valid relationships were identified due to sentence complexity and contextual variability.
- This underscores the challenges of applying RE without large, annotated clinical datasets.

## Tools Used
- **Programming Language:** Python  
- **Libraries:** spaCy, scikit-learn, NLTK, Pandas, NumPy, Matplotlib

## Repository Structure
 
- **`Project_NER_and_RE.ipynb`** # NER and relation extraction workflow  
- **`Project_Text_classification.ipynb`** # Smoking status classification models  
- **`smoking dataset.csv`** # Dataset for text classification  
- **`ClinicalAnalysis_NLP.pptx`** # Presentation summarizing findings  
- **`ClinicalAnalysis_NLP@article.docx`** # Detailed project report
- **`README.md`** # Project documentation


## Author Information
**Janaki Ramya Namburu**  
Email: janakiramyan36@gmail.com  
LinkedIn: https://www.linkedin.com/in/janakiramya  


