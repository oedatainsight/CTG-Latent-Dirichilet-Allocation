# Latent-Dirichilet-Allocation-CTG-Project
 This is the source code for the LDA project with CTG trial data


# Scientific Research Topic Modeling

A Python project for extracting, processing, and analyzing scientific research data to discover underlying topics using Latent Dirichlet Allocation (LDA). This project utilizes libraries such as NLTK, Gensim, NumPy, PyLDAvis, and spaCy to preprocess text data, perform topic modeling, and visualize the results.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project aims to provide tools for natural language processing, specifically geared towards the analysis of scientific research data. It includes functionalities for data loading, text preprocessing, topic modeling with LDA, and interactive visualization of topics.

## Installation

To run this project, you need Python 3.x and the following packages:

```bash
pip3 install nltk
pip3 install gensim
pip3 install numpy
pip3 install pyLDAvis
pip3 install spacy
Additionally, you may need to download specific NLTK data:

python
Copy code
import nltk
nltk.download("stopwords")
Usage
The script is structured as follows:

Data Loading and Writing: Functions for loading and writing JSON data.
Preprocessing: Utilizing gensim and spaCy for text cleaning and lemmatization.
Topic Modeling: Building an LDA model with gensim to identify topics within the data.
Visualization: Using PyLDAvis to visualize the topics identified by the LDA model.
To run the entire pipeline, execute the provided script in a Python environment after installing the necessary libraries.

Dependencies
Python 3.x
NLTK
Gensim
NumPy
PyLDAvis
spaCy
Contributing
Contributions to this project are welcome! Please fork the repository, make your changes, and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

License
This project is open-source and available under the MIT License. See the LICENSE file for more details.