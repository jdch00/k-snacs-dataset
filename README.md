# K-SNACS Dataset and Guidelines
**Korean Semantic Network of Adposition and Case Supersense**

## Dataset

**File:** [little_prince_ko.tsv](./little_prince_ko.tsv)

**Data Version:**  
* Current: 1.0
* Compatible with K-SNACS Guidelines v0.9

**Data Info:** 
* Title: 어린 왕자 (erin wangca) "The Little Prince"
* Author: Atoine de Saint-Exupéry 
* Original Language: French (Le Petit Prince)
* Genre: Childrens literature, Novella

**Column Description:**
* <tt>doc_id</tt>: chapter number, starts at 1
* <tt>sent_id</tt>: sentence id, starts at 1
* <tt>token_id</tt>: token id, starts at 1. Stacked postpositions receive token_id-N designation, where N is a sequencial value starting at 1 (as an example see doc_id 1, sent_id 14, token_id 1).
* <tt>form</tt>: word form
* <tt>morph</tt>: morphological analysis obtained from [KOMA Tagger](https://ieeexplore.ieee.org/document/5075772). 
* <tt>p</tt>: postposition
* <tt>gold_scene</tt>: gold adjudicated scene role label
* <tt>gold_function</tt>: gold adjudicated function label

**License:**
This dataset's supersense annotations are licensed under CC BY 4.0 ([Creative Commons Attribution-ShareAlike 4.0 International license](https://creativecommons.org/licenses/by/4.0/legalcode)).

## K-SNACS Guidelines

**File:** [k-snacs-guideline-appendix-v0.9.pdf](k-snacs-guideline-appendix-v0.9.pdf)

**Guideline Version:**
* Current: 0.9
* Compatible with [English SNACS v2.5](https://arxiv.org/abs/1704.02134)
* Please note that this document is an appendix to the above English SNACS guidelines, including only language-specific information that merits further detailing. For full definitions of labels and use cases, please refer to [English guidelines](https://arxiv.org/abs/1704.02134).


## Paper
Please cite the following when using this data:

[Hwang et al., 2020](https://www.aclweb.org/anthology/2020.dmr-1.6/):
> Hwang, Jena D., Hanwool Choe, Na-Rae Han, and Nathan Schneider. "K-SNACS: Annotating Korean adposition semantics." In Proceedings of the Second International Workshop on Designing Meaning Representations. 2020. 



## K-SNACS Team

### Key Collaborators:

* [Jena Hwang](https://jdch00.github.io/) - Allen Institute for AI
* [Na-Rae Han](http://www.pitt.edu/~naraehan/) - University Pittsburgh 
* Hanwool Choe - Georgetown University
* [Nathan Schneider](http://people.cs.georgetown.edu/nschneid/) - Georgetown University

### Special Thanks to:

* [Vivek Srikumar](https://svivek.com/) - University of Utah
* [Austin Blodgett](https://www.austinblodgett.org/) - Georgetown University


### This research was supported in part by:

* NSF award IIS-1812778
* BSF grant 2016375