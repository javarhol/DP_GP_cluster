
[![Build Status](https://travis-ci.org/ReddyLab/DP_GP_cluster.svg?branch=master)](https://travis-ci.org/ReddyLab/DP_GP_cluster)

## DP_GP_cluster

DP_GP_cluster clusters genes by expression over a time course using a Dirichlet process Gaussian process model.
    
**Please see the original master of this fork for specifics about DP_GP_cluster**

## Additions

I wanted to extract the mean gene expression curve from each cluster to correlate the individual gene expressions per cluster and ultimately determine which gene sets followed the mean expression most closely. Much of this code was courtesy of Google Gemini. The gene set analysis software I used was GSEA. This allowed me to correlate individual genes with the cluster mean and then rank them by their correlation coefficient. I have also added a new "R" folder of my specific R code if you would like to do a similar method.

    
## Citation

I. C. McDowell, D. Manandhar, C. M. Vockley, A. Schmid, T. E. Reddy, B. Engelhardt, Clustering gene expression time series data using an infinite Gaussian process mixture model. _bioRxiv_  (2017).

I. C. McDowell, D. Manandhar, C. M. Vockley, A. Schmid, T. E. Reddy, B. Engelhardt, Clustering gene expression time series data using an infinite Gaussian process mixture model. _PLOS Computational Biology_ (In revision).

## License
[BSD 3-clause](https://github.com/PrincetonUniversity/DP_GP_cluster/blob/master/LICENSE)
    
