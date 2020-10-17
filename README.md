# NLP_Learning

## What is a Named Entity?
Any word which reprsents a person, organization, location etc. is a Named Entity. Named entity recognition is a subtask of Information Extraction and is the process of identifying words which are named entities in a given text. It is also called entity identification or entity chunking

## Example
"Apple acquired Zoom in China on Wednesday 6th May 2020"

Here named entities are Apple, Zoom, China and Wednesday 6th May 2020"
Named entity recognition is the task of identifying these words from the text
Why it is important?
In order to understand the meaning from a given text (for ex a tweet or document), it is important to identify who did what to whom. Named entity recognition is the first task of identifying the words which may represnt the who, what and whom in the text. It helps in identifying the major entities the text is talking about

Any NLP task which involves automatically understanding text and acts based on it, needs Named Entity Recognition in its pipeline

## Caveat
No algorithm can 100% identify all the named entities correctly

## Three approaches
Basic NLTK algorithm
with word segmentation
with sentence segmentation
Stanford NLP NER
