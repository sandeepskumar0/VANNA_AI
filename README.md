# VANNA_AI
Vanna is a Python package that uses retrieval augmentation to help you generate accurate SQL queries for your database using LLMs

![image](https://github.com/sandeepskumar0/VANNA_AI/assets/121675942/5391f9b6-a096-4bce-85c4-b424a991411a)
Vanna works in two easy steps - train a RAG "model" on your data, and then ask questions which will return SQL queries that can be set up to automatically run on your database.

vn.train(...)
Train a RAG "model" on your data. These methods add to the reference corpus below.

vn.ask(...)
Ask questions. This will use the reference corpus to generate SQL queries that can be run on your database.
