# Inflection
Predict correct inflected forms for lemmas. This is crucial for grammatical output while performing machine translation involving  morphologically complex languages.

inflect: Implements a baseline method that returns the most likely word for each lemma as seen in the training data.

inflect-model: Implements model that used combined context of previous lemma, part of speech and parent lemma in dependency tree to predict the inflection of a given lemma. 

tree.py: Used by inflect-multiple to extract dependency tree structure from .tree files. 

grade: Computes accuracy of inflector against correct inflection data for development set.

output: Output of inflector, inflect-model, on dev and test set concatenated together.