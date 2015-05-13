# Keyword Extraction Datasets

Different datasets for developing, evaluating and testing keyword extraction algorithms.
For benchmarking performance see:
O. Medelyan. 2009. [Human-competitive automatic topic indexing](http://www.medelyan.com/files/phd2009.pdf). PhD Thesis. University of Waikato, New Zealand.

### Extracting keywords using a controlled vocabulary or a thesaurus as a source:

**NLM_500.zip**	- 500 PubMed documents with MeSH terms

**fao780.tar.gz**	- 780 FAO publications with Agrovoc terms

**fao30.tar.gz**	- 30 FAO publications, each annotated by 6 professional FAO indexers

### Free-text keyword extraction (without a vocabulary):

**citeulike180.tar.gz**	- 180 publications crawled from CiteULike, and keywords assigned by different CiteULike users who saved these publications

**SemEval2010-Maui.zip**	- [SemEval-2010 Keyphrase extraction track](http://semeval2.fbk.eu/semeval2.php?location=tasks#T6) data in Maui format

**keyphrextr.tar.gz**	- Keyphrase extraction model created using SemEval-2010 training data. This model is used in the [Maui GPL demo](http://maui-indexer.appspot.com/) when no vocabulary is selected.

### Extracting keywords using Wikipedia as a controlled vocabulary of allowed terms:

**wiki20.tar.gz** - 20 Computer Science papers, each annotated with at least 5 Wikipedia articles by 15 teams of indexers
