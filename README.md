# Analysis of wahlomat-datasets for different elections in Germany

(If the Jupyter-notebook is not shown in github, please visit:   
https://nbviewer.jupyter.org/github/Yannoik/wahlo_analysis/blob/master/wahlomat.ipynb   
or for the EU-election   
https://nbviewer.jupyter.org/github/Yannoik/wahlo_analysis/blob/master/wahlomat_EU_19.ipynb   )

This notebook calculates the overlap of answers given by all parties running for the election in Bremen 2019.

It displays the parties as a network, the layout is done with a spring algorithm, where spring-force is proportional to the answer-overlap.
  
Additionally an algorithm for finding clusters/hierarchy in networks has been used.  
sources:   
new:  
Sachsen-Election 2019: http://www.wahl-o-mat.de/sachsen2019/PositionsvergleichSachsen2019.pdf
Brandenburg-Election 2019: http://www.wahl-o-mat.de/brandenburg2019/Positionsvergleich-Brandenburg2019.pdf

old:  
Bremen: https://www.wahl-o-mat.de/bremen2019/PositionsvergleichBremen2019.pdf  
EU-election: https://www.wahl-o-mat.de/europawahl2019/PositionsvergleichEuropawahl2019.pdf  

example 1: Here is the output of the sfpd-layout-algorithm with the overlap as spring-constants for the brandenburg election:  
![](brandenburg_network.png)
example 2: Here is the output of the sfpd-layout-algorithm with the overlap as spring-constants for the sachsen election:  
![](sachsen_network.png)
