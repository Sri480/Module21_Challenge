# Module21_Challenge

## NLP and Transformers
## Project: Module 21 submission

## Description:
- Develop a SMS text classification solution using a Support Vector Classification (SVC) model. Use Gradio  to host the application, enabling users to test text messages. The application will provide feedback to users, indicating whether the text is classified as spam or not.

## Libraries:
- pandas
- sklearn.model_selection, sklearn.pipeline, sklearn.feature_extraction, sklearn.svm
- gradio

## Input dataset:
- Contains text messages with a label for 'spam' and 'ham'. A label of 'ham' indicates not spam.

## Goal:
Perform SMS classification using a pipeline with TF-IDF vectorization and Linear Support Vector Classification. Use Gradio as user interface for user to select a text and find out if the model perceives it as a spam or not spam.

## Jupyter Notebook:
- gradio_sms_text_classification.ipynb

## Output:
Gradio Interface for users to test text messages. User can input a text message. System will indicate if the text is spam or not a spam, based on model predictions.
