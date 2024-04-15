![IMDB Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/6/69/IMDB_Logo_2016.svg/1200px-IMDB_Logo_2016.svg.png)

### Project Name ###

Development of a Sentiment Analysis Tool Using Transformer Models

### Introduction ###

Given the availability of a large volume of online review data (Amazon, IMDB, etc.), sentiment analysis becomes increasingly important. In this project, a sentiment classifier is built which evaluates the polarity of a piece of text being either positive or negative.

### Approach

Data Preparation
● Download and prepare your dataset, creating training, validation, and
test splits.

● Perform necessary text preprocessing steps such as tokenization,
padding, and attention mask generation. Model Training

● Choose a pre-trained Transformer model from Hugging Face's library. ● Fine-tune the model on the training dataset for the sentiment
analysis task.

● Experiment with different hyperparameters (learning rate, batch size,
number of epochs) to find an optimal configuration. Evaluation and Analysis

● Evaluate the model's performance on the test dataset using appropriate metrics (accuracy, precision, recall, F1 score).

● Analyze the model's predictions to identify patterns in errors or misclassifications.

Model


In this research, the Roberta model developed by Liu et al. at Facebook AI was employed. Building upon the groundbreaking BERT model introduced by Devlin et al., Roberta enhances and surpasses previous benchmarks by eliminating the Next Sentence Prediction (NSP) objective. Instead, it adopts a training approach with significantly larger mini-batch sizes and learning rates. Utilizing the ubiquitous transformer architecture proposed by Vaswani et al.

RoBERTa comprises an encoder stack of L layers, each containing A self-attention heads and a hidden dimension of H. This architectural refinement contributes to the model's superior performance in natural language understanding tasks, setting new standards in the field of deep learning-based language modeling and sentiment analysis.

### Results:
- Positive       

precision: 0.93, recall: 0.91, f1-score: 0.92, accuracy: 0.92

- Negative

precision: 0.91 , recall: 0.93, f1-score: 0.92, accuracy: 0.92


