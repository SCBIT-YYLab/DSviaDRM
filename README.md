# DSviaDRM
Elucidation of human disease similarities has emerged as an active research area, which is highly relevant to etiology, disease classification, 
and drug repositioning. This package was designed and implemented for identifying disease similarities. It contains five functions which are 
'DCEA', 'DCpathway', 'DS', 'comDCGL' and 'comDCGLplot'. In 'DCEA' function, differentially co-expressed genes and differentially co-expressed 
links are extracted from disease vs. health samples. Then 'DCpathway' function assigns differential co-expression values of pathways to be the 
average differential co-expression value of their component genes. Then 'DS' employs partial correlation coefficient of pathways as the disease 
similarity for each disease pairs. And 'DS' contains a permutation process for evaluating the statistical significant of observed disease 
partial correlation coefficients. At last, 'comDCGL' and 'comDCGLplot' sort out shared differentially co-expressed genes and differentially 
co-expressed links with regulation information and visualize them. 

#
DSviaDRM is available as an R package, with a user's guide and source code, at http://cran.r-project.org/web/packages/DSviaDRM/index.html.

# Reference
Yang, J., et al. (2015). "DSviaDRM: an R package for estimating disease similarity via dysfunctional regulation mechanism." Bioinformatics 31(23): 3870-3872.

