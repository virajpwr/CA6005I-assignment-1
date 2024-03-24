# CA6005I-assignment-1
Student ID: 23102561
email: viraj.pawar2@email.dcu.ie


The notebook `assignment.ipynb` implements a simple Information Retrieval system that is able to index a small collection of documents, perform queries over it, and generate an output in the form of a ranked list of document id and for their corresponding query id. 

The notebook implements Vector Space Model (VSM), BM25 and Query Likelihood with Laplace smoothing models. 

Information on folders:

- data - This folder contains Cranfield collection, a small collection of  domain limited 1,400 abstracts and associated queries from https://github.com/oussbenk/cranfield-trec-dataset

- evaluation - This folder contains evaluation of the implemented information retrieval model using TREC evaluation programme accessed at https://github.com/terrierteam/jtreceval

- results: This folder contains results from implemented information retrieval model and the results are saved in a text file with query_id iter <space> document_id <space> rank <space> similarity <space> run_id

