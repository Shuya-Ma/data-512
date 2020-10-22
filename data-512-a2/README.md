# A2: Bias in data

## About the project
The goal of this project is to identity if any sources of bias may exist in the Wikipedia Talk corpus datasets, and to develop testable hypotheses about how these biases might impact the behavior of machine learning models trained on the data, when those models are used for research purposes or to power data-driven applications. 

## Data Source
The data used in this project is the Wikipedia Talk corpus, and it consists of three datasets. The data can be downloaded from [Figshare](https://figshare.com/projects/Wikipedia_Talk/16731). Each dataset contains thousands of online discussion posts made by Wikipedia editors who were discussing how to write and edit Wikipedia articles. Crowdworkers labelled these posts for three kinds of hostile speech: “toxicity”, “aggression”, and “personal attacks”. 

Dataset description and schemas can be found [here](https://meta.wikimedia.org/wiki/Research:Detox/Data_Release)

In this project, we are only using two of them: Toxicity and Personal Attacks datasets, which can be found in the [data](https://github.com/Shuya-Ma/data-512/tree/main/data-512-a2/data) folder.

## Result

Annotation workers of both Personal Attack and Toxicity datasets might not be inclusive enough to match the general population: much more young-aged, high education-level and English speaking male crowdworkers are included. Gender bias is the one issue we focused in this project. Moreover, there is also a difference labelling behaviors among workers in different gender group: female tends to have a higher possibily to label the comments as a personal attack or toxic.

All the output plots can be found in the [plot](https://github.com/Shuya-Ma/data-512/tree/main/data-512-a2/plot) folder.

## License
[Wikimedia](https://meta.wikimedia.org/wiki/Research:Detox/Data_Release#Personal_Attacks) and [Figshare](https://figshare.com/projects/Wikipedia_Talk/16731)

These datasets are released under a [CC0 public domain dedication](https://wiki.creativecommons.org/wiki/CC0)

## Citation
Wulczyn, Ellery; Thain, Nithum; Dixon, Lucas (2016): Wikipedia Detox. figshare. doi.org/10.6084/m9.figshare.4054689