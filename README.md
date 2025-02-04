# Flask Controlled Vocabulary App
This is a Flask application that converts sentences into a controlled vocabulary format using LangChain and ChatOllama. It allows users to upload an Excel file with sentences or manually input a sentence to get structured results.

# Features
Upload an Excel file (.xlsx) to process multiple sentences.

Enter a single sentence and get a structured output.


The app will return structured output in the format:
- When: [condition]
- If: [condition]
- Then: [result]

Uses LangChain, Flask, Pandas, and ChatOllama.

Runs on Google Colab, and can be deployed using Ngrok.
