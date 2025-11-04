The dataset contains legal documents and contracts collected from various sources. The data includes a variety of legal documents such as privacy policies, merger agreements, and non-disclosure agreements. Using these, we can build upon a base of precedents and domain knowledge.

 

The documents are present as text files (.txt) in the corpus folder. There are four types of documents in the corpus folder, divided into four subfolders.

contractnli: contains various non-disclosure and confidentiality agreements
cuad: contains contracts with annotated legal clauses
maud: contains various merger/acquisition contracts and agreements
privacy_qa: a question-answering dataset containing privacy policies
The dataset also contains evaluation files in JSON format in the benchmark folder. The files contain the questions and their correct answers, along with sources. For each of the above four folders, there is a JSON file: contractnli.json, cuad.json, maud.json, privacy_qa.json.

Data Loading, Preparation and Analysis [20 marks]

Data Understanding
Understand the data for documents and queries, and associated answers.
Load and Preprocess the data [5 Marks]
Load all ’.txt’ files from the folders.
Preprocess the text data to remove noise and prepare it for analysis.
Exploratory Data Analysis [10 Marks]
Calculate the average, maximum and minimum document length
Analyse the frequency of occurrence of words and find the most and least occurring words.
Analyse the similarity of different documents to each other based on TF-IDF vectors.
Document Creation and Chunking [5 Marks]
Perform appropriate steps to split the text into chunks.
Vector Database and RAG Chain Creation [15 marks]

Vector Embedding and Vector Database Creation [7 marks]
Initialise an embedding function for loading the embeddings into the vector database.
Load the embeddings to a vector database.
Create a RAG chain [8 marks]
Create a RAG chain.
Create a function to generate an answer for the asked questions.
RAG Evaluation [10 marks]

Evaluation and Inference [10 marks]
Extract all the questions and all the answers/ground truths from the benchmark files.
Create a function to generate an answer for the asked questions.
Draw inferences by evaluating answers to all questions.
Conclusion [5 marks]

Conclusions and insights [5 marks]
Conclude with the results here. Include the insights gained about the data, model pipeline, the RAG process and the results obtained.​​​​​​​
