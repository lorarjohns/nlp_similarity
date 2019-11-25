<h1 align="center">Strategies for semantic similarity</h1>
<p>
</p>

> Natural Language Processing of Paraphrases
## About

This notebook outlines potential approaches to the notoriously difficult problem of how to identify the features that contribute to natural language understanding in machine learning -- what makes AI "understand" language, rather than robotically process it?

## Install

```sh
$ git clone https://www.github.com/lorarjohns/nlp_similarity.git
```

## Usage

The easiest way to run this notebook may be to use the Docker container available at [this repo](https://github.com/ml-tooling/ml-workspace): 

```sh
$ docker run -p 8080:8080 mltooling/ml-workspace:latest
```

Inside the container, you'll need to install the spaCy pretrained word vectors from the command line. The easiest way to do so is by running:

```sh
$ pip install spacy-transformers & python -m spacy download en_trf_bertbaseuncased_lg
```

Alternatively, you're welcome to try out the Docker Compose cookiecutter available at [my GitHub repo](https://github.com/lorarjohns/cookiecutter_compose):

```sh
$ cookiecutter https://github.com/lorarjohns/cookiecutter_compose.git
```

### Requirements and Packages:

- spaCy
- tensorflow
- pytorch
- torch
- json
- numpy
- pandas
- jq

## Author

👤 **Lora Johns**

* Github: [@lorarjohns](https://github.com/lorarjohns)