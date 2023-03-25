# Information Retrieval - With Boolean Retreival Algorithm
### What is Boolean Retreival Model?
The Boolean Query Model is a common approach for information retrieval, where a search query is constructed using Boolean operators such as AND, OR, and NOT to retrieve relevant documents from a collection of information resources. This model is based on the idea that a document either satisfies or does not satisfy a query based on the presence or absence of specific terms in the document.

In this project, we focus on text-based indexing, where we index the content of the documents based on the words they contain. The indexing process involves breaking down the text into individual words or terms, removing stop words, and stemming the remaining words to their root form. The resulting index contains a list of terms, and for each term, a list of documents that contain the term.

To perform a search using the Boolean Query Model, we take the user's query and convert it into a Boolean expression using the Boolean operators. We then search the index to retrieve documents that satisfy the Boolean expression. The result is a list of relevant documents that match the user's query.
---

![image](https://user-images.githubusercontent.com/75899822/227687683-5d1140ee-f2db-4aa3-9158-22e941645a68.png)

## Getting Started:
---

#### Dependencies:
* Install Python 3.8 or above
* Install all pip requirements from the requirements.txt:
```
cd info-retrieval
pip install -r requirements.txt
```
or 
```
pip install nltk==3.7
pip install streamlit
```
