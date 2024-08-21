# 🧙‍♂️ Harry Potter Social Network Analysis

## 🛠 Project Overview:

This project involves an in-depth social network analysis of the characters in the Harry Potter universe. By constructing and analyzing a network graph, the project reveals insights into the relationships between characters across all seven books of the series. The analysis applies various network science techniques to uncover the most influential characters and the overall structure of the social network.

**This project is strictly connected to the following project by shecodespython:**

## 🚀 Key Components:

### Data Preparation:

- Constructed a network from the co-occurrence of characters within a five-sentence window in the text.
- Nodes represent characters, while edges represent the relationships between them, weighted by the frequency of their co-occurrences.
- Analyzed a dataset with 254 nodes (characters) and 606 edges (relationships).

### Network Properties:

- **Diameter:** Analyzed the longest shortest path in the network, discovering a diameter of 9, indicating the longest chain of character relationships.
- **Connected Components:** Identified 11 connected components, with the largest containing 232 nodes, which became the focus of further analysis.
- **Average Degree:** Calculated an average degree of 5.12, suggesting moderate connectivity among characters.

### Centrality Measures:

- **Degree Centrality:** Highlighted characters with the most direct connections. Harry Potter and Dobby were identified as highly connected nodes.
- **Betweenness Centrality:** Identified key characters who act as bridges within the network, with Harry Potter again standing out as a central figure.
- **Closeness Centrality:** Measured how close a character is to all others in the network, with Harry Potter having the highest closeness centrality, indicating efficient communication potential.
- **Eigenvector Centrality:** Evaluated the influence of characters based on their connections to other important nodes, with Dobby and Harry Potter showing high influence.
- **PageRank:** Assessed overall importance and influence within the network, with Harry Potter leading in PageRank centrality.

### Distribution Analysis:

- Analyzed the distribution of centrality measures, clustering coefficients, and degree centrality across the network.
- Visualized these distributions to understand the spread of influence and connectivity among the characters.
  
### Network Visualization:

- Created visual representations of the network, highlighting the most central characters and the structure of their relationships.
- Visualizations included degree distribution plots, clustering coefficient histograms, and centrality distribution graphs.

## 📊 Skills Demonstrated:

- Social Network Analysis
- Centrality Metrics and Network Properties
- Data Visualization and Interpretation
- Application of NetworkX, Matplotlib and PyVis for Network Science
