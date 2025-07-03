# ESG Text Classification in Vietnamese Using Pre-trained Language Models


## Overview
The fine-tuned ESG classifier achieved an accuracy of **99.64%** in a 4-class classification task covering:


- **E**: Environmental 
- **S**: Social 
- **G**: Governance 
- **I**: Irrelevant 


To evaluate the effectiveness of the proposed model, experiments were conducted, showing two key results:


1. The model demonstrated **high generalization performance**, achieving 99.64% accuracy on sectors not included in the training data. 
2. It was able to **accurately extract ESG-related content** from report text data.


The training dataset was compiled from reputable sources using manual labeling and further expanded through pseudo-labeling techniques.
---


## 🧪 Pretrained Models Used


This project fine-tuned and evaluated multiple Vietnamese and multilingual transformer models:


- ✅ viDEBERTA 
- ✅ viELECTRA 
- ✅ PhoBERT-Base 
- ✅ viBERT 
- ✅ ViSoBERT 
- ✅ BERT-Base Multilingual 
- ✅ RoBERTa 
- ✅ DistilBERT-Multilingual 
- .......
---


## 📁 Dataset


The dataset consists of ESG-related texts manually labeled into one of four classes:


- **E**: Environmental 
- **S**: Social 
- **G**: Governance 
- **I**: Irrelevant



Additional content was translated from high-quality global ESG corpora to Vietnamese and expanded using pseudo-labeling techniques to enrich coverage and improve generalization. 


Link: [Trungdjoon/Vietnam-ESG](https://huggingface.co/datasets/Trungdjoon/Vietnam-ESG)
---


## 📊 Evaluation


- **Task**: 4-class text classification (Environmental, Social, Governance, Irrelevant) 
- **Best Model Accuracy**: **99.64%** 
- **Metrics Used**:
 - Accuracy 
 - F1-score 
 - Confusion Matrix 


The model was evaluated on both in-domain and out-of-domain sectors to verify robustness and generalization.


---


## 📌 Future Work


- Expand the ESG dataset to include more diverse formats (e.g., reports, news articles, social media) 
- Improve cross-domain robustness and multilingual capabilities 
- Deploy the ESG classifier in real-time systems for ESG monitoring and alerting 