# ChromatinEntropy
R script to analyse the entropy of a chromatin feature among an image dataset
The initial script for computing Shannon Entropy is described in DOI: 10.1186/s12915-022-01264-9 and is available at https://osf.io/9mcwg/. The script was adapted by Dr Olivier Gandrillon (ENS Lyon, France) for computing entropy of chromatin features. When all cells (segmented nuclei) express the same value for a given feature, this feature’s entropy will be null. The more cell-to-cell variability for a given chromatin feature, the higher value of entropy. 
