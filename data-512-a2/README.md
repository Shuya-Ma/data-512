# A2: Bias in data

## About the project
The goal of this project is to identity if any sources of bias may exist in the Wikipedia Talk corpus datasets, and to develop testable hypotheses about how these biases might impact the behavior of machine learning models trained on the data, when those models are used for research purposes or to power data-driven applications. 

## Data Source
The data used in this project is the Wikipedia Talk corpus, and it consists of three datasets. Each dataset contains thousands of online discussion posts made by Wikipedia editors who were discussing how to write and edit Wikipedia articles. Crowdworkers labelled these posts for three kinds of hostile speech: “toxicity”, “aggression”, and “personal attacks”. 

Dataset description and schemas can be found [here](https://meta.wikimedia.org/wiki/Research:Detox/Data_Release)

In this project, we are only using two of them: Toxicity and Personal Attacks datasets, which can be found in the [data](https://github.com/Shuya-Ma/data-512/tree/main/data-512-a2/data) folder.

## Result

There is a gender bias in annotation workers of both Personal Attack and Toxicity datasets: much more male crowdworkers are included. Moreover, there is also a difference labelling behaviors among workers in different gender group: female tends to label the comments as a personal attack and toxic more likely.

All the output plots can be found in the [plot](https://github.com/Shuya-Ma/data-512/tree/main/data-512-a2/plot) folder.

## License
[Wikimedia](https://meta.wikimedia.org/wiki/Research:Detox/Data_Release#Personal_Attacks) and [Figshare](https://figshare.com/articles/Wikipedia_Talk_Labels_Personal_Attacks/4054689)