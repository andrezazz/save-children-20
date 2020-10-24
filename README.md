# Text Analytics on News from the Rohingya Refugee Crisis

This repository contains work done as a part of a hackathon in the fall of 2020, cosponsored by [Save the Children](https://www.savethechildren.org/) and the [UVA School of Data Science](https://datascience.virginia.edu/pages/hacking-human-rights). This is a small project, focused on text mining from news resources, building a pipeline to usable text data, and performing introductory topic modelling on the resulting data, and this README is an explanation of the file strucutre of the repository.  

## Notebooks
In the project, we have three notebooks: `NYT`, `Pipeline`, and `Analysis`. Their contents are as follows:
### NYT
In the `NYT.ipynb` notebook, the New York Times APIs are employed in order to search their articles, so as to build a corpus of relevant documents.
### Pipeline
In the `Pipeline.ipynb` notebook, we query a [free online news API](https://newsapi.org/) to build another corpus, and we extract and perform cleaning operations on the text of the relevant news stories.
### Analysis
In the `Analysis.ipynb` notebook, we use the cleaned text data to perform Latent Dirichlet Analysis topic modelling on each corpus. This notebook also generates a handful of .html
files, which are interactive visual represenations of the topic models.

## License
This project is licensed under the terms of the MIT license.
