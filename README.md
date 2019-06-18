# Visualisation of MCA results from FactoMineR using Plotly
A script for automatic visualisation of MCA results from FactoMineR in 3 dimensions using Plotly (exported as html). 

This script contains a function that transforms the results of FactoMineR's MCA function to a structure that can be used by plotly, and then creates and exports in html format six 3d scatterplots, namely: Contributions of Categories, Contributions of Individuals, Coordinates of Categories, Coordinates of Individuals, Cosine Squared of Categories and Cosine Squared of Individuals.

The function, in order to work, must be supplied with:
1) A list that contains the results of an MCA function of FactoMineR
2) One of three valid plotting methods of plotly's 3d scatterplot ("lines", "markers" or "linesmarkers").
