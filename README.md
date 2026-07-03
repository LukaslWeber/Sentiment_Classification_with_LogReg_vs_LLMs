# Sentiment Classification with TF-IDF + Logistic Regression and LLMs

This project compares methods for sentiment classification, the task of determining the emotion of texts. <br>
It uses the IMDB dataset to compare two methods: 
1. A simple method that combines TF-IDF vectors and Logistic Regression and
2. A DistilBERT model that is further fine-tuned on sentiment classification in this project.

It compares both methods against each other and works out advantages and disadvantages between both.

The project demonstrates that that a simple, efficient model (TF-IDF + Logistic Regression) shows a strong performance with minimal computational requirements.
DistilBERT offers a high accuracy and generalizes better to unseen and more diverse data, but does so at the cost of increased complexity. 
This highlights the advantages of transformer architectures for text classification tasks and their ability to understand context of sentences or whole paragraphs. 
<br>
The results also show that for data with clean, well-balanced labels - such as the IMDB dataset - simple and efficient models work surprisingly well and may be suited for resource-constrained environments or use cases requiring low latency.

