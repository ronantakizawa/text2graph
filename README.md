# text2graph
Graph Neural Network for Error Detection in LLM-generated Knowledge Graphs

This Jupyter notebook uses Langchain's LLMGraphTransformer to take a text input and form it into a knowledge graph. The knowledge graph is then used to train a Graph Neural Network (GNN) that classifies nodes into clusters. This allows the GNN to then detect any anomaly nodes in the knowledge graph. 

Example: a cluster with 1 node is likely to be a anomaly and an error in the input text. 

Useful for:
- Anomaly Detection (Remove errors from knowledge graphs)
- Knowledge Graph Validity Verification (Verify the quality of knowledge graph generated by an LLM)
- Data Cleansing (Remove outlier data in knowledge graphs)
  
