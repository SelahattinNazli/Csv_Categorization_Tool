# Csv_Categorization_Tool
This project is designed to read a bank statement from a CSV file, categorize the transactions based on predefined categories, and generate Python code to sum the categorized data. The project utilizes OpenAI's GPT-3.5 model to automate the categorization of transactions and then generates Python code to further process the data.

**Project Overview**

The code consists of several key components:

**OpenAI Integration:**
This project uses OpenAI's GPT-3.5 model via the langchain-openai library to process and categorize the bank statement transactions. The LangChain framework is used to chain LLM prompts and provide sequential outputs.

**Dynamic Categorization:** 

The transactions in the CSV file are processed and categorized into predefined categories such as:

Groceries
Transport
Entertainment
Shopping
Utilities
Eating Out
Unknown
Automated Python Code Generation: After categorizing the data, the project generates Python code that sums the transactions by category, making it easier to analyze and report on the financial data.
