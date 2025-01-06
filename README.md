# Knowledge Graphs: Building and Querying with Neo4j and LangChain

This repository provides a hands-on guide for building and querying Knowledge Graphs using Neo4j and LangChain. It complements the Medium article titled *Knowledge Graphs: Building and Querying with Neo4j and LangChain*, offering all necessary code and resources.

For more details, read my article on Medium: [Knowledge Graphs: Building and Querying with Neo4j and LangChain](https://medium.com/@elmahfoudradwane/knowledge-graphs-building-and-querying-with-neo4j-and-langchain-cffc2683e737).

## Overview

Knowledge Graphs represent entities as nodes and relationships as edges, providing a natural way to model and analyze complex systems. This project demonstrates:

- Creating nodes and relationships in Neo4j.
- Transforming textual data into graph structures.
- Querying the Knowledge Graph using LangChain for natural language interaction.

## Features

- **Knowledge Graph Creation**: Create nodes and relationships using Neo4j and Cypher queries.
- **Data Import**: Import external datasets to enrich your graph.
- **Natural Language Queries**: Use LangChain to interact with the Knowledge Graph via natural language.

## Setup Instructions

### Prerequisites

- Python 3.8+
- Neo4j (Cloud or Local Instance)
- Jupyter Notebook

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/aquam503/knowledge-graphs-neo4j-langchain.git
   cd knowledge-graphs-neo4j-langchain
   ```

2. Configure your Neo4j database connection by setting the following environment variables:
   ```bash
   export NEO4J_URI="neo4j+s://<your-database-uri>"
   export NEO4J_USERNAME="<your-username>"
   export NEO4J_PASSWORD="<your-password>"
   ```

### Running the Notebook

1. Open the Jupyter Notebook.

2. Follow the step-by-step instructions in the notebook to build and query the Knowledge Graph.

## Example Queries

### Query 1: Actors in a Movie
```plaintext
Who acted in Ironman?
```

### Query 2: Director of a Movie
```plaintext
Who was the director of the movie GoldenEye?
```

## Applications

- **Personalized Recommendations**: Suggest movies or products based on user preferences.
- **Semantic Search**: Enhance search engines with contextual understanding.
- **Dynamic Q&A Systems**: Enable intelligent question-answering using AI and Knowledge Graphs.

## License

This project is licensed under the [MIT License](LICENSE).

## References

- [Medium Article: Knowledge Graphs: Building and Querying with Neo4j and LangChain](https://medium.com/@elmahfoudradwane/knowledge-graphs-building-and-querying-with-neo4j-and-langchain-cffc2683e737)

