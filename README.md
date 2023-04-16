# question-generator
T5 based Question Generator - TURB phase 2

Uses SQuAD v2 dataset to train for generating questions from a given context. 

Also utilizes the run time fine tuning with human interaction on the fly 

Hosted model on huggingface.co 

This repository contains a T5 based Question Generator machine learning model. The model can generate natural and relevant questions for a given passage of text. This can be useful for creating quizzes, assessments, or study guides from any source of information.

The model is trained on the SQuAD dataset, which consists of over 100,000 question-answer pairs based on Wikipedia articles. The model uses the T5 framework, which is a text-to-text transformer that can perform various natural language processing tasks by using different prefixes. For question generation, the model takes a passage as input and outputs a question with the prefix "generate question: ".

The code for the model is available in the python notebook in this repository. Everything is commented out in the notebook, so you don't have to worry about how to install or run the model. You can simply open the notebook in Google Colab and run the cells to see the results. You can also modify the input passages and see how the model generates different questions for them.