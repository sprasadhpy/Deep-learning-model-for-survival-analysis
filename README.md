# Deep-learning-model-for-survival-analysis

- The International Accounting Standards Board (IASB) revised their accounting standards for financial instruments, such as loans or mortgages, in response to the 2008   financial crisis in the United States and Europe. 
- This resulted in the International Financial Reporting Standard 9, which became effective on or after January 1, 2018. The new standard requires banks to build      
  provisions for expected losses in their loan portfolio, using a more forward-looking approach that aims to result in a more timely recognition of credit losses. -  -- Previously, impairment losses were only recognized to the extent of objective evidence of impairment, meaning a loss event needed to occur before an impairment loss 
  could be booked. 
- To implement the new accounting rules, banks need to build models that can accurately evaluate a borrower's risk, with the probability of default being a key credit   risk parameter. 
- Classification techniques such as logistic regression and decision trees can be used to classify risky and non-risky loans, but survival analysis is needed for more   accurate credit risk calculations as it estimates the time it takes for a customer to default.


[Slides]: <a href="https://github.com/sprasadhpy/Deep-learning-model-for-survival-analysis/blob/main/LD-PR02.pdf" target="_blank">Deep-learning-model-for-survival-analysis</a>

[Notebook]: <a href="https://github.com/sprasadhpy/Deep-learning-model-for-survival-analysis/blob/main/Deep%20learning%20for%20survival%20models-Copy1.ipynb" target="_blank">DeepSurv-PCHazard-CoxCC</a>


## Results: ##

### Pycox[DeepSurv Library] ###
Survival probabilities 

![Pycox](https://user-images.githubusercontent.com/40602129/219292293-947ef923-ca96-4edf-bedf-e2c26aaced84.JPG)


###  Piecewise Constant Hazard (PC-Hazard) model ###
Survival probabilities 

![Piecewise Constant Hazard (PC-Hazard) model](https://user-images.githubusercontent.com/40602129/219292463-8c6968e5-820f-49d9-a8a6-9b27dce78db4.JPG)



### Coxx CC method ###
Survival probabilities 

![CoxCC](https://user-images.githubusercontent.com/40602129/219292516-1eab1059-5622-4d0e-82af-240559011bf7.JPG)
