# wp3-semantic-parsing-Dutch
Robust semantic parsing Dutch (state-of-the-art natural language processing pipeline) 

- [Word Sense Disambiguation](https://github.com/cltl/svm_wsd): system based on Support Vector Machines to assign senses and a system confidence score to words. 
- [Entity recognition, classification][https://github.com/ixa-ehu/ixa-pipe-nerc] & [linking][https://github.com/ixa-ehu/ixa-pipe-ned]: identifies names in text, assigns a type such as person, location or organisation and tries to anchor it to its DBpedia resource (DBpedia [http://wiki.dbpedia.org] is a graph database that contains the structured information from Wikipedia) 
- [Ontotagger][https://github.com/cltl/OntoTagger]: module that inserts ontological labels to Wordnet synsets associated with terms or directly to the lemmas of the term based on the external resources provided.
- Semantic Role Labelling (event extraction): identifies and classifies the semantic arguments in a sentence, for example who was the perpetrator of an action and who was the subject, as well as locations which can be used to generate event descriptions 
- [Factuality/Attribution][]: qualifies the certainty (certain/probable/possible) of an event, whether the event is confirmed or denied (pos/neg) and whether it is in the future (future/non-future)
- [Opinion extraction][https://github.com/rubenIzquierdo/opinion_miner_deluxePP]: detects opinion entities (holder, target and expression)
- [Simple tagger][https://github.com/cltl/SimpleTagger]: generic tagger that identifies concepts in text and links this to external references. It currently comes with a basic version to tag Historical Occupations (from [Hisco][https://socialhistory.org/en/projects/hisco-history-work]) and identify family relations for Dutch
- [NLP2RDF crystallisation strategies][https://github.com/cltl/EventCoreference]: resolves coreference of entities and events within and across documents to generate event descriptions based on the [Simple Event Model][http://semanticweb.cs.vu.nl/2009/11/sem/]. 

We have other modules available, contact marieke.van.erp@vu.nl for more information. 

