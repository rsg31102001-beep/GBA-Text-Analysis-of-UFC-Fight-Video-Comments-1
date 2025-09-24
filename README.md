This project contains a Jupyter Notebook that preprocesses a dataset of UFC-related comments. The notebook demonstrates text cleaning and preparation techniques commonly used in natural language processing (NLP) tasks, laying the groundwork for sentiment analysis and further text-based studies.

Features
Load UFC comments dataset from Excel
Handle missing values in the text column
Convert text to lowercase
Remove special characters and noise
Tokenize comments into words
Remove stopwords using NLTK
Save cleaned dataset for further analysis

Requirements
Make sure you have the following Python libraries installed:
pip install pandas nltk openpyxl

Usage
Clone this repository:
git clone https://github.com/yourusername/UFC_Dataset.git
cd UFC_Dataset
Open the Jupyter Notebook:
jupyter notebook UFC_Dataset.ipynb
Update the file path inside the notebook to point to your UFC dataset Excel file.
Run the cells step by step to clean and preprocess the comments.

Output
A cleaned version of the dataset is generated with additional processed columns such as:
comment_lowercase
comment_no_special_chars
comment_tokens (tokenized text)
comment_cleaned (stopwords removed)
The cleaned dataset is saved as UFC_Dataset2.xlsx for further analysis.

Future Work
Sentiment analysis of UFC comments
Visualization of word frequencies and patterns
Building machine learning models for text classification
