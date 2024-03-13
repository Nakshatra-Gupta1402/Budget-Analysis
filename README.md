# Budget-Analysis

Project Overview
This Jupyter Notebook project focuses on analyzing the Indian Budget Report for the year 2024. The project involves various tasks such as web scraping, text summarization, sentiment analysis, information extraction, and more. The aim is to provide insights and understanding into the key highlights and aspects of the budget for the specified year.

Project Components

1. Web Scraping
The project begins with web scraping to extract text data from the Indian Budget Report 2024 webpage. Python libraries such as `requests` and `BeautifulSoup` are utilized for this task. The extracted text includes key highlights and updates regarding the budget.

2. Text Summarization
A text summarization task is performed using the `transformers` library, specifically utilizing the BART-large model. The summary provides a concise overview of the budget report, highlighting key points such as fiscal targets, tax rates, expenditure allocations, etc.

3. Sentiment Analysis
Sentiment analysis is conducted on the extracted text to determine the sentiment associated with different segments of the budget report. The `transformers` library is again used for this task, employing a text classification model to classify text segments into positive, negative, or neutral sentiments.

4. Information Extraction
Information extraction is performed to identify specific entities or tasks mentioned in the budget report. The `transformers` library is utilized, employing a token classification model to label entities such as tasks, agents, etc., mentioned in the text.

Implementation Details
The project is implemented in a Jupyter Notebook environment using Python programming language. The following libraries are used throughout the project:
- `requests`: For making HTTP requests to fetch web content.
- `BeautifulSoup`: For parsing HTML content.
- `bleach`: For cleaning HTML content.
- `transformers`: For utilizing pre-trained models for text summarization, sentiment analysis, and information extraction.
- `nltk`: For tokenization.
- Regular Expressions (regex): For text cleaning and preprocessing.

Conclusion
The Budget Analysis project in the Jupyter Notebook provides a comprehensive approach to analyzing the Indian Budget Report for the year 2024. By employing various natural language processing techniques such as web scraping, text summarization, sentiment analysis, and information extraction, valuable insights are gained into the key aspects and sentiments associated with the budget report. This documentation serves as a guide to understand the project workflow and its components.
