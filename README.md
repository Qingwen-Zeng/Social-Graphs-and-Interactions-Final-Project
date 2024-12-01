# Social-Graphs-and-Interactions-Final-Project

*One Piece* is a globally renowned Japanese anime and manga series created by Eiichiro Oda. Set in a vast and vibrant world of pirates, it follows Monkey D. Luffy and his crew, the Straw Hat Pirates, as they embark on thrilling adventures in pursuit of the legendary treasure, the "One Piece." Spanning over 25 years, the series boasts a richly developed narrative, hundreds of unique characters, and intricate relationships across diverse factions and arcs. This complex and dynamic storytelling makes *One Piece* an ideal subject for exploring social graphs and natural language processing techniques.

#### **Why *One Piece* Is an Intriguing Choice for Social Graphs**
1. **Complex Relationship Web**:
   * *One Piece* features hundreds of characters, each interconnected through various relationship types, including alliances, rivalries, familial bonds, and hierarchical ties.
   * Crews such as the Straw Hat Pirates, the Marines, and the Yonko networks exhibit dense and layered internal structures, making them ideal for graph-based analysis.
   * Inter-crew and inter-arc interactions, such as alliances during the War of the Best or conflicts in Wano, add another layer of complexity.

2. **Dynamic Evolution of the Graph**:
   * The narrative spans over 25 years and 1000+ episodes, featuring evolving relationships and arcs. Nodes (characters) and edges (relationships) emerge, change, or disappear over time.
   * Analyzing such dynamic graphs can provide insights into how alliances form and dissolve or how centrality metrics evolve throughout the story.

3. **High Diversity in Communities**:
   * Each crew or faction represents a community with distinct characteristics. For instance, the Straw Hats function as a close-knit family, while the Marines operate within a rigid hierarchy.
   * Understanding the structure and properties of these subgraphs can highlight social cohesion, power dynamics, and role centrality.

---

#### **Relevance of NLP Analysis in *One Piece***
1. **Sentiment Analysis of Characters and Crews**:
   * By analyzing dialogues and narrative descriptions, sentiment analysis can reveal the emotional undertones of specific relationships or arcs.
   * For instance, how does the sentiment associated with the Straw Hat crew compare to that of the Blackbeard Pirates? Are some arcs (e.g., Skypiea vs. Marineford) associated with higher positivity or negativity?
   
2. **Themes and Personality Extraction**:
   * Character dialogues may also reveal thematic elements, such as justice, freedom, or betrayal, central to specific factions or arcs.
   * NLP techniques can help identify the unique linguistic style of characters or groups, such as Luffy's simplicity versus Doflamingo's eloquence.

3. **Bridging Social Graphs and Textual Analysis**:
   * Linking sentiment or thematic data to graph nodes allows for multidimensional character analysis. For example:
     - Are emotionally central characters also structurally central in the graph?
     - How do crew-wide sentiments correlate with their narrative role (e.g., heroes vs. villains)?

---

#### **Basic A Priori Elements of the Networks**
1. **Nodes (Characters)**:
   * The graph's nodes will represent individual characters, each enriched with attributes such as:
     - **Name**
     - **Faction/Crew** (e.g., Straw Hat Pirates, Marines)
     - **Primary Role** (e.g., Captain, Swordsman, Admiral)
     - **Arc Participation** (e.g., Alabasta, Dressrosa)

2. **Edges (Relationships)**:
   * Edges will represent various types of relationships between characters:
     - **Alliance**: Crewmates or allies (e.g., Luffy and Zoro)
     - **Conflict**: Enemies or rivals (e.g., Luffy and Blackbeard)
     - **Family**: Familial ties (e.g., Luffy and Garp)
   * Weighted edges can reflect relationship strength (e.g., frequency of interaction).

3. **Attributes of the Graph**:
   * **Communities**: Crews and factions will naturally cluster as communities within the graph.
   * **Temporal Dynamics**: Some relationships are arc-specific and evolve over time.
   * **Centrality Measures**:
     - Key characters like Luffy, Zoro, or the Yonko are expected to have high betweenness or degree centrality.

4. **Estimated Scale**:
   * **Nodes**: Likely in the range of 500–1000, given the extensive character list in *One Piece*.
   * **Edges**: Potentially several thousand, considering both direct and indirect relationships.

---

#### **Potential Research Questions and Applications**
1. **Graph Analysis**:
   * What are the most influential characters or crews based on centrality metrics?
   * How do different arcs reshape the overall graph structure?

2. **Sentiment and Language Insights**:
   * What are the sentiment trends across key arcs (e.g., does sentiment decline during Marineford)?
   * How do factions differ in their use of language and themes?

3. **Combined Insights**:
   * Can sentiment data help predict relationship strength or evolution?
   * How do central characters' emotional tones influence the surrounding network?

---

#### **Why This Matters**
Studying the *One Piece* universe using social graphs and NLP not only provides a rich and engaging application of these theories but also serves as a model for analyzing large, dynamic fictional worlds. Furthermore, insights from such analyses can be extended to real-world scenarios, such as understanding community structures, social dynamics, and sentiment evolution in large-scale networks.

