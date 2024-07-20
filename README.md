## Text Summarizer
## Overview
The Text Summarizer project aims to provide concise and informative summaries of news articles. This tool is especially useful for aspirants and busy individuals who need to stay updated with the latest news without spending too much time reading lengthy articles. By summarizing the text, it saves time and effort while ensuring that users remain informed.

## Motivation
The motivation behind creating this project was to develop a tool that could help users quickly grasp the essential points of news articles. This is particularly beneficial for aspirants who need to stay informed about current events but may not have the time to read full articles. The summarizer ensures that they can get the critical information they need efficiently.

## Tech Stack
The project utilizes the following technologies and libraries:

-Python: Programming language used for implementation.
-Hugging Face Datasets: For loading and processing the dataset.
-Transformers: To leverage pre-trained models for text summarization.
-Pandas: For data manipulation and analysis.
-Accelerate: For efficient training on hardware accelerators.

## Key Features
-Automated Text Summarization: Automatically generates summaries for provided news articles.
-Pre-trained Model: Uses the t5-small pre-trained model for summarization.
-Data Preprocessing: Efficiently preprocesses the input text for better model performance.
-Training and Evaluation: Includes functionalities for training the model on custom datasets and evaluating its performance.
-Inference: Provides a method for predicting summaries of new documents

## Libraries
pip install datasets transformers accelerate pandas
