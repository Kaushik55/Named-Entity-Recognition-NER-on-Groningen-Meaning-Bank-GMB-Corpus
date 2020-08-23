# Introduction

NER is the task of identifying useful information (entities) in text and categorising them into categories like names of persons, organizations, locations, time, quantities, monetary values and percentage. Entity can be a word or sequence of words in a sentence. Named-entity recognition is also known as entity identification, entity chunking and entity/information extraction. With the application of NER, a high level overview of any document can be obtained. 

## Business Problem

### Objective: 
Given a sentence as input, the objective here is to classify each word in the given sentence into pre defined classes of entities. 

### Data:
GMB dataset corpus is tagged, annotated and built specifically to train the model which can predict named entities such as name, location, etc.
Source-https://www.kaggle.com/abhinavwalia95/entity-annotated-corpus?select=ner_dataset.csv

Essential info about entities:

-geo = Geographical Entity

-org = Organization

-per = Person

-gpe = Geopolitical Entity

-tim = Time indicator

-art = Artifact

-eve = Event

-nat = Natural Phenomenon

Above class of entities are labeled using the BIO scheme, where each entity label is prefixed with either B or I letter. B- denotes the beginning and I- inside of an entity. The words which are not of interest are labeled with 0.

### Challenge metric
Accuracy is used as metric to train the model 
