Building Knowledge Graph using Spacy.

PDF Text Extraction: The script extracts text from multiple PDF files using PyPDF2 and processes them into sentences with spaCy.

DataFrame Creation: All sentences are stored in a pandas DataFrame for further processing.

Entity Extraction: It identifies subject and object entities in sentences using dependency parsing via spaCy.

Entity-Pair Collection: Extracted subject-object pairs are stored as entity pairs.

Relationship Extraction: A custom spaCy matcher identifies relationships (verbs) between entity pairs.

Knowledge Graph DataFrame: A DataFrame with entities (source, target) and relationships (edges) is created.

Graph Construction: NetworkX builds a directed graph using the entity and relation DataFrame.

Visualization: Matplotlib visualizes the graph with nodes (entities) and edges (relations).

Filtering: Specific relationships (e.g., "used") are filtered for targeted visualization.

Objective: This builds a knowledge graph from text for insights into entity relationships. 


