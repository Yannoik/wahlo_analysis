# Analysis of the wahlomat-data of the election in Bremen, Germany 2019

(If the Jupyter-notebook is not shown in github, please visit:   
https://nbviewer.jupyter.org/github/Yannoik/wahlo_analysis/blob/master/wahlomat.ipynb   
or for the EU-election   
https://nbviewer.jupyter.org/github/Yannoik/wahlo_analysis/blob/master/wahlomat_EU_19.ipynb   )

This notebook calculates the overlap of answers given by all parties running for the election in Bremen 2019.

It displays the parties as a network, the layout is done with a spring algorithm, where spring-force is proportional to the answer-overlap.
  
Additionally an algorithm for finding clusters/hierarchy in networks has been used.  
sources:   
Bremen: https://www.wahl-o-mat.de/bremen2019/PositionsvergleichBremen2019.pdf  
EU-election: https://www.wahl-o-mat.de/europawahl2019/PositionsvergleichEuropawahl2019.pdf  

As example: Here is the output of the sfpd-layout-algorithm with the overlap as spring-constants:
![](sfdp_couplings.png)
