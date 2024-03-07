# ADL4

This project contains a Recipe Retrieval System utilizing a combination of Sentence-BERT (SBERT) for generating meaningful text embeddings and LanceDB for efficient vector search, the system provides relevant, recipe suggestions from a database of recipes. 
This approach ensures that users receive recipes that closely match their search criteria, whether they are looking for something specific or exploring new culinary ideas.

# Key Features includes:
**Advanced Text Processing:** Incorporates tokenization, stop word removal and lemmatization to enhane the system's understanding of user input.

**Semantic Embedding Generation:** Uses SBERT to convert recipe data and user queries into vector representations, capturing the nuanced semantics of culinary terms and phrases.

**Efficient Vector Search:** Employs LanceDB to perform fast and accurate vector similarity searches, quickly retrieving the most relevant recipes based on the query embeddings.

**Flexible Query Handling:** Supports a variety of query types, from concise dish names to verbose descriptions and contextual requests, accommodating a broad spectrum of user needs.

**User Interface:** Features a Gradio-based web interface that offers a straightforward and intuitive way for users to interact with the system, enter queries, and view recipe suggestions.
