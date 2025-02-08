# SmartPaper
This project focuses on leveraging NLP techniques to assess the publishability of research papers and recommend suitable conferences. The model utilizes TF-IDF, Logistic Regression, SciBERT embeddings, FAISS similarity search, and BART-based text summarization to achieve high accuracy and explainability.

Project Overview
Objective: Assess the publishability of research papers and recommend well-matched conferences based on the content of the papers.
Key Components:
Publishability Classification: TF-IDF and Logistic Regression are used to classify research papers based on their publishability.
Conference Recommendation: SciBERT embeddings and FAISS similarity search are employed to recommend conferences like CVPR, NeurIPS, EMNLP, KDD, TMLR, and DAA based on content similarity.
Summarization: BART-based text summarization is used to generate a concise explanation for each conference recommendation, improving decision-making and model transparency.
Features
Research Paper Classification: Classifies research papers as publishable or non-publishable with high accuracy using TF-IDF and Logistic Regression.
Conference Matching: Recommends the top conference(s) based on paper content using SciBERT embeddings and FAISS similarity search.
Explainable Recommendations: BART summarization model provides reasoning for conference recommendations, enhancing the interpretability of the system.
Technologies Used
Python
Natural Language Processing (NLP):
TF-IDF Vectorizer
Logistic Regression
SciBERT embeddings
FAISS similarity search
BART-based text summarization
Libraries:
Hugging Face Transformers
Scikit-learn
FAISS
Pandas, NumPy
PyTorch
Results
Publishability Classification: Achieved high accuracy in classifying papers as publishable or non-publishable.
Conference Recommendation: Recommended conferences like CVPR, NeurIPS, EMNLP, KDD, TMLR, and DAA with good alignment to paper topics.
Explainability: The BART summarization model provided clear justifications for each recommendation, aiding in transparency and decision-making.
Contribution
Feel free to fork the repository, create a pull request, and contribute improvements or bug fixes. Contributions are welcome!
