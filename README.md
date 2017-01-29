# Entity Resolution in Unstructured Data
## and applications in the analysis of historical documents
*by Benjamin van der Burgh*

Entity resolution is the process of finding records in one or more datasets that relate to the same entity. In a project that was carried out in collaboration with The National Archives (UK), this problem was studied in the context of historical documents, with the aim of linking together personal information that is scattered throughout different documents.

In this master project the different challenges in performing entity resolution in this specific context were studied: usually only a name appears in a text, which can furthermore contain errors that were introduced in the transcription process. A context-free grammar was used to extract references to people and limited contextual information from the text as tabular records. A classification algorithm, based on pair-wise comparison of the individual fields of the records of two candidate pairs, was used to group candidate pairs into matching and non-matching. An unsupervised feature extraction procedure, using Maximally k-Informative Itemsets, was used to extract topics from the documents in an attempt to improve the performance of the algorithm.

### Download
A copy of my thesis can be downloaded from [here](https://github.com/benjaminvdb/master_thesis/raw/master/main.pdf).

### License
This work is licensed under a [Creative Commons "Attribution-ShareAlike 4.0 International" license](https://creativecommons.org/licenses/by-sa/4.0/).
