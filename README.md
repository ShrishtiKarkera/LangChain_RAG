## LangChain RAG to query github docs

To use the source code:

Step 1: <br>
Clone the repository
```
git clone git@github.com:ShrishtiKarkera/LangChain_RAG.git
```

Add your OPENAI_API_KEY <br>
This queries Github Docs - https://github.com/github/docs/tree/main <br>
Any set of documents can be queried - AWS, GCP, etc. <br>

Step 2: Install dependencies
```python
pip install -r requirements.txt
```

Step 3: Create the vector database - Chroma in this case
```python
python create_database.py
```

Step 4: Query the database 
```python
python query_data.py "How does Alice meet the Mad Hatter?"
```
