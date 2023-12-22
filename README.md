# Natural Language Processing on Steam Reviews

## Project Overview

This project focuses on Natural Language Processing (NLP) applied to Steam reviews, aiming to extract meaningful insights and improve language understanding. The following key points highlight the major contributions and techniques employed:

1. **Data Cleaning:**
   - Cleaned a Kaggle dataset comprising 1.6 million Steam reviews. Non-English and short reviews were removed to enhance the quality of the dataset.

2. **Text Preprocessing:**
   - Lemmatized all reviews and employed a TF-IDF tokenizer to generate a document-term matrix. This preprocessing step is crucial for feature extraction and subsequent analysis.

3. **Similarity Analysis:**
   - Implemented a cosine-similarity algorithm to identify the top five most similar reviews to a given input review. This aids in understanding review patterns and identifying similar player sentiments.

4. **GPT2 Fine-tuning:**
   - Utilized TensorFlow and the GPT2-Simple library to fine-tune a GPT2 model specifically on Steam reviews. This step involves training the model to better comprehend and generate coherent language based on the unique characteristics of Steam reviews.

5. **Prompt Engineering:**
   - Engineered prompts for the GPT2 model to perform specific tasks, such as summarizing sets of reviews or game descriptions. This enables the model to provide concise and informative summaries based on user-defined input.

## Notebooks

### 1. Steam_Reviews_Cleaning_And_Similarity.ipynb

This notebook focuses on the initial steps of the project, including:

- **Data Cleaning:**
  - The cleaning process for the Steam reviews dataset, including the removal of non-English and short reviews to enhance data quality.

- **Stratification:**
  - Stratifying the dataset to ensure a balanced representation of reviews across different categories or labels.

- **Similarity Analysis:**
  - Implementation of a code snippet that finds similar reviews from the stored dataset based on an input review from the user. The cosine-similarity algorithm is employed for this task.

### 2. GPT_Train_FINAL.ipynb

This notebook details the training process of the GPT2 model. It consists of three iterations, each focusing on refining the model and improving its performance. Key features include:

- **Fine-tuning with TensorFlow:**
  - Utilizing TensorFlow and GPT2-Simple library for the fine-tuning process.

- **Model Iterations:**
  - Three iterations of training, each showcasing the progress and outcomes of the GPT2 model. Test outputs are provided to evaluate the model's performance.

### 3. Frontend.ipynb

This notebook is dedicated to creating a user-friendly frontend for interacting with the trained models. It includes:

- **Streamlit Integration:**
  - Utilizing the Streamlit library to build an interactive and locally hosted frontend.

- **Ngrok Integration:**
  - Setting up Ngrok to expose the locally hosted frontend to the internet, allowing for external access.

- **User Input and Output:**
  - Allowing users to input a review and receive similar reviews and game recommendations. Additionally, incorporating GPT2-powered summaries of the input reviews.
