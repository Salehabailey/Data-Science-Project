# Hate Speech Detection using LLM

## Aim of the Project

This research aims to develop a trustworthy and effective system for detecting hate speech using state-of-the-art natural language processing methods. Leveraging Byte Pair Encoding (BPE) for subword representation and ELMo (Embeddings from Language Models) for contextual word embeddings, the BERT transformer model will be employed to accurately detect and categorize hate speech within textual content by combining these advanced methodologies.

## Research Questions for the Project

- How does the combination of BERT with ELMo and BPE improve the accuracy and robustness of hate speech detection compared to using BERT alone?
- What is the importance of Byte Pair Encoding (BPE) and ELMo in enhancing the detection of hate speech, especially in the context of neologisms, vernacular, and misspellings?

## Objectives of the Project

- **Examination of Methodologies:** Perform a comprehensive review of current hate speech detection methods to identify deficiencies and potential areas for improvement.
- **Data Collection and Preprocessing:** Collect and preprocess a varied dataset encompassing both hate speech and non-hate speech, ensuring comprehensive text standardization for consistency and quality.
- **Implementation of Advanced NLP Techniques:** Apply the ELMo model to capture contextual word embeddings for deeper semantic understanding, and implement Byte Pair Encoding (BPE) to handle infrequent words, neologisms, and spelling errors efficiently.
- **Model Development and Evaluation:** Develop a robust hate speech detection system using the BERT transformer model, optimizing it for maximum classification accuracy, and evaluate its performance using metrics like accuracy and loss.

## Motivation for the Project

The motivation for hate speech detection is rooted in the desire to create safer and more inclusive online communities. Social media and digital platforms often spread harmful content that endangers marginalized groups and society. By developing sophisticated detection methods, this project aims to protect vulnerable populations and foster online civic discourse. Additionally, this project aligns with my career aspirations in AI and NLP, contributing to the development of ethical AI practices and enhancing my expertise in language models. The societal impact and potential for professional growth make this research both rewarding and essential.

## Methodology

This study follows a systematic approach to developing an efficient hate speech detection system using the BERT model. The project starts with the collection of data from 'A Curated Hate Speech Dataset.' The next step is data preparation, which involves cleaning and normalizing the text to ensure consistency. Feature extraction is then carried out using advanced methods such as Byte Pair Encoding (BPE) and ELMo. Following this, the BERT model is developed and fine-tuned for optimal performance. The final step involves performance evaluation, assessing the model's effectiveness using metrics such as accuracy and loss.

![Methodology Flowchart](./img/Picture1.jepg)

## How to Run the Code

### Prerequisites

Make sure you have the following packages installed:
- pandas
- re
- emoji
- num2words
- nltk
- matplotlib
- seaborn
- wordcloud
- sklearn
- imblearn
- tensorflow
- transformers
- tokenizers

### Steps to Run the Code

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-repo/hate-speech-detection-LLM.git
2. Use requirements.txt to install required packages
3. Open jupyther notebook
4. Navigate to the cloned location
5. Open Model_development.ipynb file
