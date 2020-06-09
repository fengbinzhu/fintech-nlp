# NLP Progress in Financial Domain 

The research and progress of Natural Language Processing (NLP) in Finance Domain (FinTech).


## Workshops

* FinIR (SIGIR): Information Retrieval in Finance 
  * [2020](https://finir2020.github.io/)
* FNP (COLING): Financial Narrative Processing
  * [2020](http://wp.lancs.ac.uk/cfie/fnp2020/)
  * [2019](https://wp.lancs.ac.uk/cfie/fnp2019/)
  * [2018](http://wp.lancs.ac.uk/cfie/fnp2018/)
* KDF (AAAI): Knowledge Discovery from Unstructured Data in Financial Services
  * [2020](https://aaai-kdf2020.github.io/)
* FinNLP(IJCAI): Financial Technology and Natural Language Processing
  * [2020](https://sites.google.com/nlg.csie.ntu.edu.tw/finnlp2020/)
  * [2019](https://sites.google.com/nlg.csie.ntu.edu.tw/finnlp/home)
* ECONLP (EMNLP): Economics and Natural Language 
  * [2019](https://sites.google.com/view/econlp-2019)
  * [2018](https://julielab.de/econlp/2018/)
* Robust AI in FS (NeurIPS)
  * [2019](https://sites.google.com/view/robust-ai-in-fs-2019/home)
* ADF (KDD): Anomaly Detection in Finance
  * [2019](https://sites.google.com/view/kdd-adf-2019)  
  * [2017](https://sites.google.com/view/kdd-adf-2017)

## Tasks

There are various NLP tasks that have been developed in financial domain.

### Sentiment Analysis

* [Financial Phrase Bank](https://www.researchgate.net/publication/251231364_FinancialPhraseBank-v10)

Each example sentence is classifed into a positive, negative or neutral category by considering only the information explicitly available in the given sentence. Since the study is focused only on financial and economic domains, the sentences are considered from the view point of an investor only; i.e. whether the news may have positive, negative or neutral influence on the stock price. As a result, sentences which have a sentiment that is not relevant from an economic or financial perspective are considered neutral.

### Summarizing 

* [Financial Narrative Summarisation (FNS) in FNP 2020](http://wp.lancs.ac.uk/cfie/fns2020/)

The volume of available financial information is increasing sharply and therefore the study of NLP methods that automatically summarise content has grown rapidly into a major research area.

The Financial Narrative Summarisation (FNS 2020) aims to demonstrate the value and challenges of applying automatic text summarisation to financial text written in English, usually referred to as financial narrative disclosures. The task dataset has been extracted from UK annual reports published in PDF file format.

The target of this task is to produce one summary for each annual report. The summary length should not exceed 1000 words. Both extractive and abstractive summary are acceptable.


### Question Answering (QA)
TBD 

### Information Extraction

* [Causality & Effect Extraction(FinCausal) in FNP 2020](http://wp.lancs.ac.uk/cfie/fincausal2020/)
 
Financial analysis needs factual data, but also explanation on the variability of these data. Data state facts, but provide little to no knowledge regarding how these facts materialised. The Financial Document Causality Detection Task aims to develop an ability to explain, from external sources, the reasons why a transformation occurs in the financial landscape, as a preamble to generating accurate and meaningful financial narrative summaries. Its goal is to evaluate which events or which chain of events can cause a financial object to be modified or an event to occur, regarding a given external context. This context is available in the financial news, but due to the high volatility of such information, mapping an external cause to a given consequence is not trivial.

* Event extraction

TBD

* Relation Extraction
TBD

### Sentence Boundary Detection(SBD)

 * FinFBD-1st in FinNLP 2019
 
Sentences are basic units of the written language and detecting the beginning and end of sentences, or sentence boundary detection (SBD) is a foundational first step in many Natural Language Processing (NLP) applications, such as POS tagging; syntactic, semantic, and discourse parsing; information extraction; or machine translation.

This task focuses on extracting well segmented sentences from Financial prospectuses by detecting their beginning and ending boundaries. These are official PDF documents in which investment funds precisely describe their characteristics and investment modalities. The most important step of extracting any information from these files is to parse them to get noisy unstructured text, clean it, format information (by adding several tags) and finally, transform it into semi-structured text, where sentence boundaries are well marked.

[Papers](https://sites.google.com/nlg.csie.ntu.edu.tw/finnlp/accepted-papers?authuser=0#h.p_aztToN6iKsM4)

 * [FinFBD-2nd in FinNLP 2020](https://sites.google.com/nlg.csie.ntu.edu.tw/finnlp2020/shared-task-finsbd-2?authuser=0)
 
In addition to an improved version of the previously proposed task, this task is extended to include the detection of lists and list items, as well as their hierarchy in this year.

FinSBD'2 is split into two sub-tasks:
  - Extracting sentence boundaries, including list and list item boundaries.
  - Organizing the lists items hierarchically.

### Semantic Representations

* [FinSim in FinNLP 2020](https://sites.google.com/nlg.csie.ntu.edu.tw/finnlp2020/shared-task-finsim?authuser=0)
In this task, participants will be given a list of carefully selected terms from the Financial domain such as “European depositary receipt”, “Interest rate swaps” and will be asked to design a system which can automatically classify them into the most relevant hypernym (or top-level) concept in an external ontology. For example, given the set of concepts “Bonds”, “Unclassified”, “Share”, “Loan”, the most relevant hypernym of “European depositary receipt” is “Share”.

Participants will be given a large corpus of in-domain data to facilitate learning semantic representations as well as a set of concepts extracted from an ontology ([The Financial Industry Business Ontology (FIBO)](https://spec.edmcouncil.org/fibo/)).


## Corpus
  
 * [Reuters Corpora (RCV1, RCV2, TRC2)](https://trec.nist.gov/data/reuters/reuters.html)

   * _RCV1_: Reuters Corpus Volume 1, contains about 810,000 Reuters, English Language News stories
   * _RCV2_: Reuters Corpus Volume 2, contains over 487,000 Reuters News stories in thirteen languages (Dutch, French, German, Chinese, Japanese, Russian, Portuguese, Spanish, Latin American Spanish, Italian, Danish, Norwegian, and Swedish).
   * _TRC2_: Thomson Reuters Text Research Collection, comprises 1,800,370 news stories covering the period from 2008-01-01 00:00:03 to 2009-02-28 23:54:14.

 * [Fin10k](https://drive.google.com/drive/folders/1tKLUPczYH81vD67NDWEFvnEWD9bEc6tO)
    electronic filings for each company each year.

## Pretrained LM Models in Financial Domain
 * FinBERT: Language model trained on `TRC2` [Link](https://github.com/ProsusAI/finBERT)
 * FinBERT: Pre-Trained on SEC Filings for Financial NLP Tasks on `Fin10k`, [Link](https://github.com/psnonis/FinBERT)

## Resources 
 * [Annual Reports](http://www.annualreports.com/)
 * [Financial Industry Business Ontology (FIBO)](https://spec.edmcouncil.org/fibo/OWL)
 *

## Applications
TBD

## Reference

* [Repository](https://github.com/icoxfog417/awesome-financial-nlp)
