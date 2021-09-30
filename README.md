# Lasso for covariate selection in capture-recapture models

Material for a talk about using lasso for covariate selection in capture-recapture models. 

* [Slides](slides/GimenezRenner-Lassotalk.pdf)
* [Video recording](video-recording/gimenezrenner-lasso-videorecording.mp4)
* [Transcript](transcript/transcript-lassocapturerecapture.txt)

**Authors**:    
Gimenez, Olivier – CNRS Montpellier, France    
Renner, Ian – The University of Newcastle, Australia

**Abstract**:    
Capture-recapture models are widely used in statistical ecology for inferring population dynamics of plants and animals with imperfect individual detection. These models allow covariates to be incorporated to try and explain variation in demographic parameters like, e.g., survival or dispersal.

When dealing with several covariates however, analysts are often faced with the issue of selecting relevant ones. In particular, incorporating many covariates in a model may result in a loss of power in detecting a significant effect as well as a decrease in the precision associated with its magnitude.

Here, we explore regularization techniques to perform covariate selection in capture-recapture models. We implement the lasso to select a subset of the covariates for use in the inference. The lasso works by maximizing the likelihood, which is penalized via some constraints on the covariate parameters. We provide a number of criteria to judge the bias-variance tradeoff.

The performance of our approach is analyzed by conducting a simulation study to assess the effect of the number of covariates. We also illustrate our approach with a real case study.

Our proposal requires minor modifications to the likelihood and could be implemented in standard capture-recapture software.
