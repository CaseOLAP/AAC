## Exploration of Post-translational modifications (PTMs) through knowledge graph approach.

### Description: 

Knowledge Graphs can link diverse sets of data and facts, reveal new relationships, and suggest mechanisms for further study. In this project, various data sets (e.g., Proteins, PTM Types, Pathways, Associated Compounds, References, Organism) are extracted from biomedical databases and systematically integrated into the Knowledge Graph (KG). In the first place, integrated KG assists in the advanced search and implementation of graph algorithms for underpinning hidden relationships and biomarkers. (e.g., centrality, community). Next, KG becomes the underlying infrastructure for developing advanced graph-based machine learning (e.g., Graph Neural Network (GNN), Heterogeneous Graph Transformer (HGT)) for link prediction, which further assists in predicting new PTM types for the proteins.

![img](img/schema.png)

### Use case: 

Post-translational modifications (PTMs), particularly the oxidative modifications at cysteine residues, can have profound effects on the activity, stability, and interaction of proteins. Understanding oxidative modifications at cysteine residues in crucial mitochondrial ADP/ATP carrier proteins could provide key insights into disrupted cellular energy regulation, affecting conditions like cardiovascular and metabolic diseases. The current knowledge of PTM identification of proteins are mainly based on experimental technique like mass spectrometry and are usually studied in isolation. There's a need for a comprehensive view that connects these PTMs to functional outcomes in the cellular context. 

### Project Walkthrough:
- Understand the schema, data content, and development of the knowledge graph in the interface of Cardiovascular Disease, CVD drus, drug target proteins and underlying molecular mechanism.
- Learn more about graph embedding functionality in Neo4j GDS library and DGL-KE library.
- Learn more about the fundamentals of machine learning models ( e.g., allocating data for training, validation, and test, selecting proper GNN message passing algorithm, selecting optimizer, Cost function, accuracy metric, and inferences).
- Explore about homogeneous Graph Neural Network with provided tutorial-1.
- Explore heterogeneous Graph Neural Networks with provided tutorial-2.
- Develop the graph embedding for the heterogeneous knowledge graph.
- Prepare the training, validation, and testing by masking the nodes or edges.
- Train the model with tuning hyperparameters and interpret the performance.
- Implement the model for link prediction and analyze it with biomedical findings.


### Educational Goal:

This project offers the wonderful opportunity to learn and build cutting-edge machine learning models in graph data. Participants will get hands-on experience with GNN and KG libraries (e.g., Neo4j, DGL, and Pytorch Geometric).

### Scientific Goal:

Understanding the role of drug in Cardiovascular Disease through a molecular mechanism and adverse effects associated drug target proteins is the core of the scientific goal of the project. Prediction of the possible links between Drug and Drug target proteins/ Drug and Diseases opens a new research horizon. Newly predicted associations could provide further insight into the molecular mechanism and disease pathogenesis.

### References

Learning HeteroGraph Pytorch Gemometric
Introduction to Knowledge Graph Embedding
Graph Embedding in Neo4j
