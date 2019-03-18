# question-answering-system

## Pre requisite

Please make sure you have docker installed and running

## Installation

Please clone this repository using the following command. This will clone and initialise all the submodules  
git clone --recurse-submodules -j8 https://github.com/qasim9872/question-answering-system.git

To run all the microservices, run the following command:  
docker-compose up (Run with sudo if necessary)

## USEFUL COMMANDS

Update all submodule to match the latest remote commit  
git submodule update --remote --merge

Initialise and updates the submodules recursively  
git submodule update --init --recursive

## Citations

The following were used for generating the dataset including pairs of english sentences with the associated SPARQL query.

```
@inproceedings{soru-marx-2017,
    author = "Tommaso Soru and Edgard Marx and Diego Moussallem and Gustavo Publio and Andr\'e Valdestilhas and Diego Esteves and Ciro Baron Neto",
    title = "{SPARQL} as a Foreign Language",
    year = "2017",
    journal = "13th International Conference on Semantic Systems (SEMANTiCS 2017) - Posters and Demos",
    url = "http://w3id.org/neural-sparql-machines/soru-marx-semantics2017.html",
}
```

```
@inproceedings{soru-marx-nampi2018,
    author = "Tommaso Soru and Edgard Marx and Andr\'e Valdestilhas and Diego Esteves and Diego Moussallem and Gustavo Publio",
    title = "Neural Machine Translation for Query Construction and Composition",
    year = "2018",
    journal = "ICML Workshop on Neural Abstract Machines \& Program Induction (NAMPI v2)",
    url = "https://arxiv.org/abs/1806.10478",
}
```

The Python Api uses the following library for training the data, and exposing it as a rest api.

```
@article{nmt-keras:2018,
 journal = {The Prague Bulletin of Mathematical Linguistics},
 title = {{NMT-Keras: a Very Flexible Toolkit with a Focus on Interactive NMT and Online Learning}},
 author = {\'{A}lvaro Peris and Francisco Casacuberta},
 year = {2018},
 volume = {111},
 pages = {113--124},
 doi = {10.2478/pralin-2018-0010},
 issn = {0032-6585},
 url = {https://ufal.mff.cuni.cz/pbml/111/art-peris-casacuberta.pdf}
}
```
