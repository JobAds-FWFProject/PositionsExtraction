# PositionsExtraction
Code and data accompanying the paper 'Extracting position titles from unstructured historical job advertisements' that deals witih extracting job titles from historical job advertisements. The advertisements are predominantly in German and spanning from 1850-1950. The code contains the entire pipeline for training model (NER approach), resp. establishing the rules (rule-based and dictionary-based approach). 

Models performance on testing dataset is as follows:

| Method | Accuracy |
|--------|----------|
| Dictionary-based approach | 55.37% |
| Rule-based approach | 69.07% |
| NER approach (CPU) | 84.36% |
| NER approach (GPU) | 92.16% |


The model trained on GPU cannot be uploaded because of its size, however, we are sharing the model trained on CPU that reaches 87.42% accuracy in identifying job titles in historical job advertisements. For all details, please see the paper.


Training and Testing data contain the jov ads text and as annotated entities the position titles within them. The data were used from the following newspapers:
- Arbeiterwille (https://anno.onb.ac.at/cgi-content/anno?aid=awi)
- Freie Stimmen (https://anno.onb.ac.at/cgi-content/anno?aid=fst)
- Grazer Tagblatt (https://anno.onb.ac.at/cgi-content/anno?aid=gtb)
- Illustrierte Kronen Zeitung (https://anno.onb.ac.at/cgi-content/anno?aid=krz)
- Linzer Volksblatt (https://anno.onb.ac.at/cgi-content/anno?aid=lvb)
- Morgen-Post (https://anno.onb.ac.at/cgi-content/anno?aid=mop)
- Neuigkeits-Welt-Blatt (https://anno.onb.ac.at/cgi-content/anno?aid=nwb)
- Prager Abendblatt (https://anno.onb.ac.at/cgi-content/anno?aid=pab)
- Reichspost (https://anno.onb.ac.at/cgi-content/anno?aid=rpt)
- Salzburger Chronik für Stadt und Land (https://anno.onb.ac.at/cgi-content/anno?aid=sch)
- Salzburger Volksblatt: die unabhängige Tageszeitung für Stadt und Land Salzburg (https://anno.onb.ac.at/cgi-content/anno?aid=svb)
- Vorarlberger Landes-Zeitung (https://anno.onb.ac.at/cgi-content/anno?aid=vlz)
- Vorarlberger Volks-Blatt (https://anno.onb.ac.at/cgi-content/anno?aid=vvb)
- Wiener Zeitung (https://anno.onb.ac.at/cgi-content/anno?aid=wrz)
