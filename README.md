# MSK_Precision_Medicine_Challenge
#### Collin Wiles, Steve Russo, Allan Dong
*************
## About
https://www.kaggle.com/c/msk-redefining-cancer-treatment

A lot has been said during the past several years about how precision medicine and, more concretely, how genetic testing is going to disrupt the way diseases like cancer are treated.

But this is only partially happening due to the huge amount of manual work still required. Memorial Sloan Kettering Cancer Center (MSKCC) launched this competition, accepted by the NIPS 2017 Competition Track,  because we need your help to take personalized medicine to its full potential.

Once sequenced, a cancer tumor can have thousands of genetic mutations. But the challenge is distinguishing the mutations that contribute to tumor growth (drivers) from the neutral mutations (passengers). 

Currently this interpretation of genetic mutations is being done manually. This is a very time-consuming task where a clinical pathologist has to manually review and classify every single genetic mutation based on evidence from text-based clinical literature.

For this competition MSKCC is making available an expert-annotated knowledge base where world-class researchers and oncologists have manually annotated thousands of mutations.

We need your help to develop a Machine Learning algorithm that, using this knowledge base as a baseline, automatically classifies genetic variations.

*************

## Approach
**Objective:** 
- Predict the cancer classfication from abstracts, and other data.

**Considerations:**
- Try multiple Natural language processing tooks
- Try several classification algorithms
- Try supplementing with additional data

**Data:**
- Original Dataset with Gene, Mutation and Text Annotation
- Genia
- other pubmed papers for training
- oncogene

**Tools to Learn:**
- Natural Language Processing tools:
- Support Vector Machines
- [Word2Vec](https://code.google.com/archive/p/word2vec/)

**Approach**
DATA
- Explore ways to process Natural Laugage?
- Cross References? perhaps maybe later 

SOFTWARE TOOLS
- AWS

DIMENSION REDUCTION
- how to select relevant features

MODEL
- Different iterations of Random Forests
- SVC
