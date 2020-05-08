## ontology-driven-TL ##
Data and resources for FOIS2020 paper: Ontology-Driven Cross-Domain Transfer Learning - https://fois2020.inf.unibz.it/

### Processes 
This folder contains the two main components used in the experiment: 
#property predictor
#class predictor

The two xml file can be run within the RapidMiner Framework: https://rapidminer.com/

For the set-ip of the feature extractor component please chek RapidMiner extension like http://splab.cz/en/download/software/immi-rapidminer-extenison 

### Ontologies
This folder contains the ontologies used in the experiment, i.e., the "Household" and "Travel" ontologies. 

Converting the given ontologies into a set of triples and filtering the triple by the "Domain" predicate it is possible to derive the matrices used to train the class predictor and to annotate each example of the image dataset.

### Data

This folder contains:
#the matrices derived from the ontologies to train the class predictor (notice that each matrix is used for each trial, i.e., SoA, Domain, TLO).
#the training set to give as input of the property predictor
#the test set to be used as test input of the class predictor

### Reference
If you found this resources helpful, please consider citing:

[Ontology-Driven Cross-Domain Transfer Learning]
@inproceedings{}

You might also want to refer to,
