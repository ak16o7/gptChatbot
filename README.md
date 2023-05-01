GPT-Based Vector Index Program
This program uses OpenAI's GPT language model to create a vector index for a collection of text documents. The vector index can be used for information retrieval tasks such as similarity search and document clustering.

# Requirements
To run this program, you will need:

Python 3.6 or later
- OpenAI API key
- Jupyter Notebook
- data stored in .txt: you can get sample data from https://gutenberg.org/

# Installation
1. Clone the repo to your local machine: git clone https://github.com//.git

2. Retrieve your OpenAI API key from https://platform.openai.com/account/api-keys and copy it into the first cell: os.environ["OPENAI_API_KEY"] = ""

# Usage
To create a vector index for a collection of text documents:

1. Place the text documents in a directory on your local machine. Put the data you want to base your chatbot on into the folder "Knowledge" (see below)

2. Update the path variable in the notebook to point to the directory containing the text documents.

3. Run the notebook cells. This will create a vector index and save it to a JSON file named vector_index.json.

To query the vector index:

- Call the answerMe function with the created vector index json file as input
This will prompt you to enter a query and return the most similar document(s) to the query.

This is how the files should be stored:
![image](https://user-images.githubusercontent.com/99226582/235485234-f9cf1d99-c30e-443e-850a-109667909edc.png)

# Examples
![image](https://user-images.githubusercontent.com/99226582/235485384-8bc4aca7-8f6a-43db-a72f-a4d4e30f6a12.png)

![image](https://user-images.githubusercontent.com/99226582/235485408-e9259588-903d-4875-ac7d-6ab51076e060.png)
