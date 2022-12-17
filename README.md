# Natural-language-to-SQL-queries
Converting natural language to SQL queries.

Natural language query system for end users The system gives accurate results for certain class of queries including relational queries, queries involving simple join conditions etc., using mappings, tokenizing and retrieving information from the English-like queries.

Quick Setup

Create and activate virtual Environment : $ virtualenv nlpSql

$ source nlpSql/Scripts/activate

Download required packages : $ pip install -r requirements.txt

Create Database
Populate it with data: python database/connection.py

Download NLTK packages : $ python

import nltk

nltk.download()

Run Server : $ python nlp-sql.py

## Future Work:
- [DONE] lexical analysis
- [DONE] syntax analysis
- [DONE] Intermediate representation
- [DONE] generation of SQL statements
- [DONE] sample input and output  queries as results
- [DONE] all references you used
- [DONE] Edit Layout frontend
- [DONE] Check dependencies frontend