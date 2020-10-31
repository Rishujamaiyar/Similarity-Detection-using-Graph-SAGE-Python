### Dataset :

This custom dataset is about the cricket players participated in the 2019 ICC Cricket World Cup .<br />
151 players from 10 countries participated in the tournament. This custom dataset is made by the players' information provided at the [news18 website](https://www.news18.com/cricketnext/icc-world-cup-2019/cricket-teams/).  


### Knowledge Graph Structure :

The Graph have a central node named (WC) for World cup.This node is linked to 10 nodes each representing one country and each country is linked to four nodes indicating the different types of players (Batsman,Bowler,All-rounder,Wicket-Keeper). All these four nodes are linked to their respective players.<br />

We are going to predict the link between any two players by using Graph Embeddings.<br />

### Expected Results :

If we consider Player 1 = Virat Kohli.<br />
Then its link with any batsman from India would be the highest.<br />
The link between other players (All-rounders/Bowlers) in Indian team would be the next closest.<br />
After that the players from different countries would be the least linked candidates.<br />

### Methodology :

For generating Node embeddings : Graph SAGE<br />
For generating Graph : Steller Graph<br />
For similarity comparison : Cosine Similarity<br />

### References :

[Inductive Representation Learning on Large Graphs](http://papers.nips.cc/paper/6703-inductive-representation-learning-on-large-graphs), Hamilton et al., NeurIPS 2017.
