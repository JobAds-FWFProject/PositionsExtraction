# PositionsExtraction
Code and data accompanying the paper 'Extracting position titles from unstructured historical job advertisements' that deals witih extracting job titles from historical job advertisements. The advertisements are predominantly in German and spanning from 1850-1950. The code contains the entire pipeline for training model (NER approach), resp. establishing the rules (rule-based and dictionary-based approach). 

Models performance is as follows:

Method  Accuracy
Dictionary-based approach  68.45%
Rule-based approach  69.08%
NER approach (CPU)  87.42%
NER approach (GPU)  93.85%

The model trained on GPU cannot be uploaded because of its size, however, we are sharing the model trained on CPU that reaches 87.42% accuracy in identifying job titles in historical job advertisements. For all details, please see the paper.
