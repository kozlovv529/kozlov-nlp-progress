# Tracking Progress in Natural Language Processing

### Table of contents

- [ASR](asr.md)
- [CCG supertagging](ccg_supertagging.md)
- [Chunking](chunking.md)
- [Constituency parsing](constituency_parsing.md)
- [Coreference resolution](coreference_resolution.md)
- [Dependency parsing](dependency_parsing.md)
- [Dialog](dialog.md)
- [Domain adaptation](domain_adaptation.md)
- [Entity Linking](entity_linking.md)
- [Grammatical Error Correction](grammatical_error_correction.md)
- [Information Extraction](information_extraction.md)
- [Language modelling](language_modeling.md)
- [Machine translation](machine_translation.md)
- [Multi-task learning](multi-task_learning.md)
- [Multimodal](multimodal.md)
- [Named entity recognition](named_entity_recognition.md)
- [Natural language inference](natural_language_inference.md)
- [Part-of-speech tagging](part-of-speech_tagging.md)
- [Question answering](question_answering.md)
- [Semantic textual similarity](semantic_textual_similarity.md)
- [Sentiment analysis](sentiment_analysis.md)
- [Semantic parsing](semantic_parsing.md)
- [Semantic role labeling](semantic_role_labeling.md)
- [Stance detection](stance_detection.md)
- [Summarization](summarization.md)
- [Taxonomy learning](taxonomy_learning.md)
- [Temporal Processing](temporal_processing.md)
- [Text classification](text_classification.md)
- [Word Sense Disambiguation](word_sense_disambiguation.md)

This document aims to track the progress in Natural Language Processing (NLP) and give an overview
of the state-of-the-art (SOTA) across the most common NLP tasks and their corresponding datasets.

It aims to cover both traditional and core NLP tasks such as dependency parsing and part-of-speech tagging
as well as more recent ones such as reading comprehension and natural language inference. The main objective
is to provide the reader with a quick overview of benchmark datasets and the state-of-the-art for their
task of interest, which serves as a stepping stone for further research. To this end, if there is a 
place where results for a task are already published and regularly maintained, such as a public leaderboard,
the reader will be pointed there.

If you want to find this document again in the future, just go to [`nlpprogress.com`](https://nlpprogress.com/)
or [`nlpsota.com`](http://nlpsota.com/) in your browser.

### Wish list

These are tasks and datasets that are still missing.

- Bilingual dictionary induction
- Discourse parsing
- Keyphrase extraction
- Knowledge base population (KBP)
- More dialogue tasks
- Relation extraction
- Semi-supervised learning
- Text normalization

### Contributing

If you would like to add a new result, you can do so with a pull request (PR). 
In order to minimize noise and to make maintenance somewhat manageable, results reported
in published papers will be preferred (indicate the venue of publication in your PR);
an exception may be made for influential preprints. The result should include the name
of the method, the citation, the score, and a link to the paper and should be added
so that the table is sorted (with the best result on top).

If your pull request contains a new result, please make sure that "new result" appears
somewhere in the title of the PR. This way, we can track which tasks are the most
active and receive the most attention.

In order to make reproduction easier, we recommend to add a link to an implementation 
to each method if available. You can add a `Code` column (see below) to the table if it does not exist.
In the `Code` column, indicate an official implementation with [Official](http://link_to_implementation).
If an unofficial implementation is available, use [Link](http://link_to_implementation) (see below).
If no implementation is available, you can leave the cell empty.

| Model           | Score  |  Paper / Source | Code | 
| ------------- | :-----:| --- | --- | 
| |  |  | [Official](http://link_to_implementation) | 
| |  |  | [Link](http://link_to_implementation) |

To add a new dataset or task, follow the below steps. Any new datasets
should have been used for evaluation in at least one published paper besides 
the one that introduced the dataset.

1. Fork the repository.
2. If your task is completely new, create a new file and link to it in the table of contents above.
If not, add your task or dataset to the respective section of the corresponding file (in alphabetical order).
3. Briefly describe the dataset/task and include relevant references. 
4. Describe the evaluation setting and evaluation metric.
5. Show how an annotated example of the dataset/task looks like.
6. Add a download link if available.
7. Copy the below table and fill in at least two results (including the state-of-the-art)
  for your dataset/task (change Score to the metric of your dataset).
8. Submit your change as a pull request.
  
| Model           | Score  |  Paper / Source | Code | 
| ------------- | :-----:| --- | --- | 
|  |  |  | | 

### Things to do

- Add a column for code (see above) to each table and a link to the source code to each method.
- Add pointers on how to retrieve data.
- Provide more details regarding the evaluation setup of each task.
- Add an example to every task/dataset.
- Add statistics to every dataset.
- Provide a description and details for every task / dataset.
- Add a table of contents to every file (particularly the large ones).
- We could potentially use [readthedocs](https://github.com/rtfd/readthedocs.org) to provide a clearer structure.
- All current datasets in this list are for the English language (except for [UD](#ud)). In a separate section, we could add
datasets for other languages.
