---
title: "GBIF LACS"
---


This is GBIF Literature Abstract Classification System

# Introduction

The objective of this project is to have a tool that allows the classification of the abstracts related to the GBIF literature.

A specific use case is the creation of a text classification model that identifies those abstracts related to host-parasite interactions and filters the literature available in the GBIF Literature API in order specifically search GBIF datasets associated with host - parasite interaction 

Another objective is to carry out a topic analysis in the abstracts of the GBIF literature and group the papers into these topics to observe the trend of research associated with GBIF in recent years.

Finally, all the information generated with these tools is available to the GBIF community for its free use in scientific research in the most open and transparent way possible, in accordance with our technical limitations.

We show here a set of tools designed to

- Find abstracts from literature stored in open data base through PubMed [entrez](https://www.ncbi.nlm.nih.gov/home/develop/api/) API and Cross Reference [crossref](https://api.crossref.org/) 
- Retrieve random abstracts from Cross Reference [crossref](https://api.crossref.org/) 

- Generate models to classify abstracts from a specific topic using PU learning approach

- Deploy a web API with a abstract classification model to evaluate whether or not a given abstract belongs to the class of modeled abstracts

- A GBIF Literature API wrap that retrives GBIF Literature information

