# City election prediction

## WHAT IS IT?

The model seeks to emulate the election campaign of three mayoral candidates in a municipality. Voting citizens, taken as rational individuals, will have to choose their preference, represented by the maximization of a linear utility function, among the three mayors. 

The model is constructed using the algebraic structure of an undirected graph, in which nodes represent each citizen and edges represent the ties between two people in the country (friendship, kinship, etc.). The concept of node centrality was also exploited, which is that property of each node that represents its importance in the graph.

## WHAT IS THE GOAL?

The goal of the model is to visualize and analyze how voter preference is affected by neighboring preferences and by past (what might be, in the case of one of the three being the outgoing mayor, the management of the country during the term just passed) and current (e.g., a scandal or fake news in the middle of the election campaign) events.

## HOW DOES IT WORK?

All commands (sliders, choosers, switchers, etc.) are placed non-randomly above and below the plot. 

The commands above the plot, which must be set before pressing 'setup', configure the characteristics of the network representing the city. In particular, it is possible to configure:
- the number of inhabitants of the city
-the number of people running for election for each mayor
-the average number of neighbors (family members, friends, etc.) that each person has in the city
-the percentage of neighbors who can influence each voter
-the percentage of young (under 35) and old (over 65) people in the town
-whether a mayoral candidate is running for re-election again. In that case, it is possible to configure which of the three is the outgoing mayor and the percentage of people satisfied and dissatisfied in the term just passed.

The commands below the plot configure each mayor's election program, that is, through the use of sliders, it is possible to set the percentage of importance that each mayor, in his or her election program, gives to the four main variables. It is also possible to specify the number of other nonprincipal variabilli.
The sliders just described must be configured before pressing the 'setup' button. There is also a 'random setup' button that randomly allows these to be configured.

Also below the plot we find other controls that set the target and intensity of a possible scandal during the campaign. The 'scandal' button must be pressed subsequent to 'go'.

## QUESTIONS OF INTEREST

How much does the electoral program influence each citizen's preference?

Does the most influential (central) citizen always belong to the winning list?

How important is the influence of neighbors in voting?

Can the presence of clusters (families) that are formed in the graph be an index that a mayor can exploit to win elections?
