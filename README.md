# sms_spam_detector

## Module 21 Challenge

### Background

You'll be refactoring code from an SMS text classification solution into a function that constructs a linear Support Vector Classification (SVC) model. Once the model is created and trained, you will create a Gradio app to host the application, enabling users to test text messages. The application will provide feedback to users, indicating whether the text is classified as spam or not, based on the model's performance.

### Files

Main jupyter notebook with gradio app is gradio_sms_text_classification.ipynb. Resources folder houses training data csv. sms_text_classification_solution.ipynb was used to supply the classification function code in main gradio notebook.

### Functions and Dependencies

This app can take a text message and predict whether it is spam or not.

import pandas as pd from sklearn.model_selection import train_test_split from sklearn.pipeline import Pipeline from sklearn.feature_extraction.text import TfidfVectorizer from sklearn.svm import LinearSVC import gradio as gr

### References

Tiago, A., Hidalgo, J. 2012. SMS Spam Collection. UCI Machine Learning Repository. Available https://archive.ics.uci.edu/dataset/228/sms+spam+collectionLinks to an external site. [2023, October 25]. (CC-BY 4.0Links to an external site.).

### Sources

- Module 21 Class Lessons
- Xpert Learning Assistant
- Classmates
- ChatGPT
