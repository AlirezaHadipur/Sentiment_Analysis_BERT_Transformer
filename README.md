# Sentiment Analysis with BERT Transformer and SST2 Dataset🎬

## Introduction📢

This project aims to perform sentiment analysis using the Stanford Sentiment Treebank (SST2) dataset and BERT (Bidirectional Encoder Representations from Transformers). Sentiment analysis is a natural language processing (NLP) technique used to determine the sentiment expressed in a piece of text, which can be positive, negative, or neutral. This project leverages BERT's advanced capabilities in understanding the context of words in sentences to improve sentiment classification accuracy.


## Background🖼

Sentiment analysis is a crucial component in many applications, such as customer feedback analysis, social media monitoring, and market research. Traditional methods often rely on bag-of-words models or simple neural networks, which may not capture the full context of the text. BERT, developed by Google, is a powerful NLP model that uses transformer architecture to understand the context of words by looking at the surrounding words (bidirectional). The SST2 dataset provides a rich source of movie review data labeled with binary sentiment, making it an ideal choice for training and evaluating our model.


## Tools I Used🛠⚒

- **Python**: The programming language used for the project.
- **PyTorch**: A deep learning framework used to build and train the BERT model.
- **Transformers Library by Hugging Face**: Used for accessing pre-trained BERT models and tokenizers.
- **Matplotlib**: A plotting library used for visualizing the results.
- **Pandas**: A data manipulation library used for handling data in CSV and JSON formats.
- **MatplotLib**: Used for visualizing the data.


## What I Learned📚

1. **Model Building and Training**: Gained hands-on experience in building and fine-tuning a BERT model using PyTorch. Learned how to handle the complexities of transformer architectures and how to effectively fine-tune pre-trained models for specific tasks.

2. **Data Preprocessing**: Understood the importance of data preprocessing steps such as tokenization, padding, and truncation when working with textual data.

3. **Working with Libraries**: Enhanced knowledge in utilizing various Python libraries, particularly the Hugging Face Transformers library, which simplifies the process of working with advanced NLP models.

4. **GitHub and Version Control**: Practiced good version control practices by regularly committing changes and documenting the project progress on GitHub.

## Conclusion📕
This project successfully demonstrates the application of BERT for sentiment analysis on the SST2 dataset. The model achieved satisfactory performance(90 Percent) in classifying sentiments, showcasing the effectiveness of BERT in understanding the contextual nuances of text. This project has deepened my understanding of NLP, transformer models, and the end-to-end process of building a machine learning model. Future work could involve experimenting with different transformer models, hyperparameter tuning, and expanding the dataset to improve the model's generalization capability.
