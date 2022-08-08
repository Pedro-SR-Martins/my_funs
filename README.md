# A repository for my functions
A repository for my randomly created functions. It is just for convenience.
  
---  
I hope this improves my productivity :)
## Functions for CFA and SEM :ghost:
This currently have three functions that help to 1) see the fit scaled fit indices (`fitis`), 2) get a nice factor loading table (`loads`), 3) see the regression coefficients of a fitted model (`show_paths`).  
source("https://raw.githubusercontent.com/Pedro-SR-Martins/my_funs/main/aux_fa")  
  
## Functions for regression models :chart_with_upwards_trend:
This currently have three functions that help to check outliers for a full linear model (`lm_out`) and for a linear model that only have factors (a.k.a. ANOVAs) (`lm_outCat`).  
You can also check the residuals distribution and check for other assumptions `lm_assump`  
source("https://raw.githubusercontent.com/Pedro-SR-Martins/my_funs/main/aux_lm")  

## A function for generalized linear models :ocean:

This currently have one function for check for outliers in generalized linear models. It is a convenience function that works similarly to the function for `lm_out`.   For now, the function `glm_out` is very simple and it was only tested for poisson models.  
It defines cooks distance as [Beaujean et al. 2016](https://scholarworks.umass.edu/cgi/viewcontent.cgi?article=1336&context=pare) and DIFFBETAS as [Belsley et al. 1980](https://onlinelibrary.wiley.com/doi/10.1002/0471725153.ch2)   
source("https://raw.githubusercontent.com/Pedro-SR-Martins/my_funs/main/aux_glm")  
