# Tutorials for using TerminusDB

> TODO: fix URL
> [![Binder-badge][][binder]

[binder-badge]: https://mybinder.org/badge_logo.svg
[binder]: https://mybinder.org/v2/gh/bollwyvl/terminusdb-tutorials/add-binder?urlpath=lab

## Installation

#### TerminusDB

Docker image available at https://github.com/terminusdb/terminus-quickstart

#### Python Client

Install using pip:

`pip install terminus-client-python`

Install from source following:
https://github.com/terminusdb/terminus-client-python

#### JavaScript Client

Install using npm following:
https://github.com/terminusdb/terminus-client

## Bike Tutorial

Using bike hire data from [here](https://www.capitalbikeshare.com/system-data) to build a graph showing different journeys

Python API script: [bike-tutorial/python](https://github.com/terminusdb/terminus-tutorials/tree/master/bike-tutorial/python)

JavaScript API script and embedding on webpage: [bike-tutorial/javascript](https://github.com/terminusdb/terminus-tutorials/tree/master/bike-tutorial/javascript)

Query and view on TerminusDB council: [bike-tutorial/view-script](https://github.com/terminusdb/terminus-tutorials/tree/master/bike-tutorial/view-script)

Also see the [tutorial blog post](https://medium.com/terminusdb/my-first-terminusdb-graph-visualisation-bike-share-data-39c59a1ab86a?source=friends_link&sk=2f877df5dcb2f00b9e4e85d5088f015e).

## Politics Tutorial

Using voting data either collected from [Dublin City Council](https://terminusdb.com/t/data/council/) or collected from [US Congress](https://terminusdb.com/t/data/congress/) to build a graph showing representatives clustered according to their voting similarities, colour coded with their political parties.

Python API script: [politics-tutorial/python](https://github.com/terminusdb/terminus-tutorials/tree/master/politics-tutorial/python)

JavaScript API script and embedding on webpage: [politics-tutorial/javascript](https://github.com/terminusdb/terminus-tutorials/tree/master/politics-tutorial/javascript)

Query and view on TerminusDB council: [politics-tutorial/view-script](https://github.com/terminusdb/terminus-tutorials/tree/master/politics-tutorial/view-script)

Also see the [tutorial blog post](https://medium.com/terminusdb/are-you-supporting-the-right-politician-b742debbc8d9?source=friends_link&sk=9dcc6e3f2fbd1a8a50a48c41510808ef).

## Schema.org Tutorial

Putting [Schema.org](https://schema.org/) vocabulary into a TerminusDB schema. Example application of putting microdata tags form html into TerminusDB graph using that schema.

Details: [schema.org](https://github.com/terminusdb/terminus-tutorials/tree/master/schema.org)

## Flight Tutorial

Putting [OpenFlights.org](https://openflights.org/) data into a TerminusDB graph.

Details: [flight-tutorial](https://github.com/terminusdb/terminus-tutorials/tree/master/flight-tutorial)

## Bank Tutorial

A generic "bank account" manipulation tutorial. Example of how to manage data via multiple branches.

In [Python](https://github.com/terminusdb/terminus-tutorials/tree/master/bank-tutorial/taking_terminus_to_the_bank.py).

Also see the [tutorial blog post](https://terminusdb.com/blog/2020/07/27/taking-terminusdb-to-the-bank/?source=friends_link&sk=9dcc6e3f2fbd1a8a50a48c41510808ef)

## Episode 2

TerminusDB's product roadmap episode 2 implementation in [python](https://github.com/terminusdb/terminus-tutorials/tree/master/episode-2/episode2.py).

## Game of Throne

In Neo4j, there is a famous example of using the Game of Throne data to create a graph visualisation of the character relations. Here we will see if we can do that in TerminusDB, and how.

Details: [game-of-thrones](https://github.com/terminusdb/terminusdb-tutorials/tree/master/game-of-thrones)

## Movies Data

Putting IMDB movie data in a graph and explore the data.

Details: [movies-data](https://github.com/terminusdb/terminusdb-tutorials/tree/master/movies-data)

## WordNet

Putting all the WordNet files (in ttl format) into TerminusDB.

Details: [wordnet](https://github.com/terminusdb/terminusdb-tutorials/tree/master/wordnet)

## SpaCy NLP [WIP]

Putting the analysis from SpaCy into a TerminusDB Graph

Details: [nlp-spacy](https://github.com/terminusdb/terminusdb-tutorials/tree/master/nlp-spacy)
