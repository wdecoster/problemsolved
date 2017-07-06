# Miniconda3 rpy2 installation

-python should be conda python (install miniconda3)  
-use conda for installation of R:  
`conda install -c r r-essentials`  
-Might have to bypass graphics of mirror selection:  
`chooseCRANmirror(graphics=FALSE)`  
-use R for installation of HardyWeinberg and mice, pointing the lib to installation dir of miniconda e.g. ~/miniconda3/lib/R/library/   
`install.packages('HardyWeinberg', "~/anaconda3/lib/R/library/")`  
-Might have to use in case of problem with connecting to mirror  
`install.packages('HardyWeinberg', dependencies=TRUE, repos='http://cran.rstudio.com/')`  
-use conda for installlation of rpy2 (or pip?)  
`conda install -c r rpy2=2.8.5`  
