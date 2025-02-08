# SmartPaper
This project focuses on leveraging NLP techniques to assess the publishability of research papers and recommend suitable conferences. The model utilizes TF-IDF, Logistic Regression, SciBERT embeddings, FAISS similarity search, and BART-based text summarization to achieve high accuracy and explainability.

**PROJECT OVERVIEW**<br>
- **Objective:** Assess the publishability of research papers and recommend well-matched conferences based on the content of the papers.<br>
- **Key Components:**<br>
- **Publishability Classification:** TF-IDF and Logistic Regression are used to classify research papers based on their publishability.<br>
- **Conference Recommendation:** SciBERT embeddings and FAISS similarity search are employed to recommend conferences like CVPR, NeurIPS, EMNLP, KDD, TMLR, and DAA based on content similarity.<br>
- **Summarization:** BART-based text summarization is used to generate a concise explanation for each conference recommendation, improving decision-making and model transparency.<br>

**FEATURES**<br>
- **Research Paper Classification:** Classifies research papers as publishable or non-publishable with high accuracy using TF-IDF and Logistic Regression.<br>
- **Conference Matching:** Recommends the top conference(s) based on paper content using SciBERT embeddings and FAISS similarity search.<br>
- **Explainable Recommendations:** BART summarization model provides reasoning for conference recommendations, enhancing the interpretability of the system.<br>

**Technologies Used:**  
- **Programming Language:** Python  
- **Natural Language Processing (NLP):**  
  1. TF-IDF Vectorizer  
  2. Logistic Regression  
  3. SciBERT embeddings  
  4. FAISS similarity search  
  5. BART-based text summarization  
- **Libraries:**  
  1. Hugging Face Transformers  
  2. Scikit-learn  
  3. FAISS  
  4. Pandas, NumPy  
  5. PyTorch  

  
**RESULTS:**<br>
- **Publishability Classification:** Achieved high accuracy in classifying papers as publishable or non-publishable.<br>
- **Conference Recommendation:** Recommended conferences like CVPR, NeurIPS, EMNLP, KDD, TMLR, and DAA with good alignment to paper topics.<br>
- **Explainability:** The BART summarization model provided clear justifications for each recommendation, aiding in transparency and decision-making.<br>

**CONTRIBUTION**<br>
Feel free to fork the repository, create a pull request, and contribute improvements or bug fixes. Contributions are welcome!
