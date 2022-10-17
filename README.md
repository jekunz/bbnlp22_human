### Human evaluation

This repo contains all files related to the human evaluation for the paper "Human Ratings Do Not Reflect Downstream Utility: 
A Study of Free-Text Explanations for Model Predictions", to appear at BlackboxNLP 2022. 

* The .csv files contain the 200 examples (respectively) from the e-SNLI and ECQA data sets along with their generated 
explanations from the GPT-ST and GPT-MT models. 
* The notebook includes all annotators' ratings, postprocessing as well as the calculations for the human evaluation scores
and Krippendorff's alpha (in the utils file, taken from https://github.com/grrrr/krippendorff-alpha), and some other stats.
