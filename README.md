# Social-Network-Analysis using R- Game of Thrones
In this project, I explored network analysis of major characters from A Storm of Swords (which is the third of seven novels in A Song of Ice
and Fire [Game of Thrones]), a fantasy series by American author George R. R. Martin. 
The books are populated by hundreds of characters enmeshed in a complex web of alliances, loyalties, histories and conflicts. 
I have tried to change this complex story into an interaction network.

Following analytical questions are being answered using network analysis:

1) Who is the most important (i.e. “influential” , “dominating “or “important”) person overall? 
The importance of characters were determined by using five distinct centrality measures. 
a) Degree b) Eigen Vector c) Closeness d) Betweenness e) Page Rank.
2) Community Detection: Applied community detection to determine the division of the network into coherent communities.
Community Detection: Applied community detection to determine the division of the network into coherent communities.
3) Identifying central actors in each community based on closeness and degree centrality.
4) Identifying the male to female ratio for separate communities.
Data: Data Source: Obtained the data from the below link: https://github.com/mathbeveridge/asoiaf/tree/master/data This link contains two files for Noel 3: book3-nodes.csv and book3-edges.csv.

Data Description: The book3-nodes.csv contains two columns Id and Label. This file has the list of all the characters in the third novel. There are total 107 rows in this file i.e. 107 unique characters. An additional column “gender” indicating gender of each character in Novel 3 was added. “1” for female and “2” for male. Added this information manually by using external data set and based on A Wiki of Ice and Fire. Both data sets contain column headers. The other file book3-edges.csv contains source and target in the first two columns and edge weight in the third column. There are total 352 rows. Nodes [id: name of the character, gender: added] • Edges [source: character, target: character, weight]
