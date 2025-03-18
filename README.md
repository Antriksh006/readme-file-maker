# 🌟 Query Assistant Project
### 🤖 _A Comprehensive Query Assistant for the Bhagavad Gita and Patanjali Yoga Sutras_

[![Python](https://img.shields.io/badge/Python-3.x-orange?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![NumPy](https://img.shields.io/badge/NumPy-1.x-blue?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.x-orange?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![Sentence Transformers](https://img.shields.io/badge/Sentence%20Transformers-1.x-blue?style=for-the-badge&logo=sentence-transformers&logoColor=white)](https://www.sbert.net/)
[![SpaCy](https://img.shields.io/badge/SpaCy-3.x-green?style=for-the-badge&logo=spacy&logoColor=white)](https://spacy.io/)
[![Groq](https://img.shields.io/badge/Groq-1.x-yellow?style=for-the-badge&logo=groq&logoColor=white)](https://groq.com/)
[![Qdrant](https://img.shields.io/badge/Qdrant-1.x-purple?style=for-the-badge&logo=qdrant&logoColor=white)](https://qdrant.tech/)

## 🌈 Overview
The Query Assistant Project is a comprehensive tool for retrieving relevant information from the Bhagavad Gita and Patanjali Yoga Sutras. The project utilizes various natural language processing (NLP) and machine learning techniques to process user queries and provide accurate responses.

## 📚 Project Structure

The project consists of several code files, each with its own unique functionality:

*   `Response for evaluation.txt`: This code file optimizes user queries for Retrieval-Augmented Generation (RAG) systems, specifically for retrieving precise and relevant verses from the Bhagavad Gita.
*   `Response for embedding_conv.txt`: This code file processes and analyzes a dataset of yoga sutras and their translations into English.
*   `Response for app.txt`: This code file creates a query assistant that returns relevant information from the Bhagavad Gita and Patanjali Yoga Sutras based on user queries.
*   `Response for storing_data.txt`: This code file loads pre-computed sentence embeddings and their corresponding enhanced sentences into a Qdrant vector database.
*   `Response for app_test.txt`: This code file provides a query assistant that processes user queries related to the Bhagavad Gita and Patanjali Yoga Sutras.

## 📝 Installation Instructions

To install the required libraries and dependencies, run the following command:

```bash
pip install numpy scikit-learn sentence-transformers spacy groq qdrant-client pinecone-client streamlit
```

## 🤔 Usage Examples

Here are a few examples of how to use the query assistant:

```python
import streamlit as st

# Define a function to process user queries
def process_query(query, collection_name):
    # Preprocess the query
    query = rewrite_query(query)

    # Search for relevant information
    results = search_collection(query, collection_name)

    # Return the results
    return results

# Create a Streamlit app
st.title("Query Assistant")

# Get user input
query = st.text_input("Enter your query")

# Get the collection name
collection_name = st.selectbox("Select a collection", ["gita", "yoga"])

# Process the query
results = process_query(query, collection_name)

# Display the results
st.write(results)
```

## 💻 Code Explanations

Here's a brief explanation of the code:

*   The `rewrite_query()` function uses the Groq API to generate rewritten queries that are more specific, contextually rich, and precise.
*   The `search_collection()` function uses the Qdrant API to search for relevant information based on the query embedding.
*   The `process_query()` function takes in a query and a collection name, rewrites the query using the `rewrite_query()` function, and then searches for relevant information using the `search_collection()` function.

## 📈 Dependencies

The project depends on the following libraries and frameworks:

*   `numpy`
*   `scikit-learn`
*   `sentence-transformers`
*   `spacy`
*   `groq`
*   `qdrant-client`
*   `pinecone-client`
*   `streamlit`

## 📚 API Documentation

Here's a brief documentation of the API endpoints:

*   `/process_query`: Process a user query and return relevant information.
*   `/search_collection`: Search for relevant information in a specific collection.

## 📊 Future Plans

Here are some future plans for the project:

*   **Integrate more NLP techniques**: Integrate more advanced NLP techniques, such as named entity recognition and part-of-speech tagging, to improve the accuracy of the query assistant.
*   **Add more collections**: Add more collections of texts to the query assistant, such as other spiritual texts or literary works.
*   **Improve the user interface**: Improve the user interface of the query assistant to make it more user-friendly and intuitive.

## 🙏 Acknowledgments

The project was built using various open-source libraries and frameworks, including `numpy`, `scikit-learn`, `sentence-transformers`, `spacy`, `groq`, `qdrant-client`, `pinecone-client`, and `streamlit`. The project also utilizes various pre-trained models and datasets, including the Bhagavad Gita and Patanjali Yoga Sutras datasets.

## 📱 Screenshots

Here are some screenshots of the query assistant:

<div align="center">
    <img src="images/Screenshot_1.png" alt="Home" width="800"/>
    <img src="images/Screenshot_2.png" alt="Query Assistant" width="800"/>
</div>

## 🙌 Contributing

Contributions are welcome! If you'd like to contribute to the project, please fork the repository and submit a pull request with your changes. Please make sure to follow the project's coding standards and guidelines.

## 📝 License

The project is licensed under the MIT License. See the LICENSE file for more information.

## 📞 Contact

If you have any questions or need help with the project, please don't hesitate to contact us. We can be reached through email at [example@email.com](mailto:example@email.com).