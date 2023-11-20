---
title: "SCRIBE - Data"
layout: gridlay
excerpt: "SCRIBE - Data"
sitemap: false
permalink: /data/
---


# Open Data
The project has a strong focus on releasing open access linguistic resources for the Norwegian language. This will be mainly achieved through the [Norwegian Language Bank (Språkbanken)](https://www.nb.no/sprakbanken/en/sprakbanken/). In this page we will collect links to the main corpora developed during the project.
* [The Norwegian Parliamentary Speech Corpus](https://www.nb.no/sprakbanken/en/resource-catalogue/oai-nb-no-sbr-84/) (NPSC) consists of 140 hours of audio files and corresponding manual transcriptions of meetings at Stortinget (the Norwegian parliament) from 2017 and 2018. The NPSC is primarily intended as an open-source dataset for ASR development.
* [The Stortinget Speech Corpus](https://www.nb.no/sprakbanken/en/resource-catalogue/oai-nb-no-sbr-91/) (SSC) can be seen as an extension of the NPSC. It consists of more than 5000 hours of speech segments with transcriptions which are automatically extracted from the official proceedings of Stortinget. It also includes metadata about the speakers extracted from the [ParlaMint-NO corpus](https://www.nb.no/sprakbanken/en/resource-catalogue/oai-nb-no-sbr-77/).
* [NB Samtale](https://www.nb.no/sprakbanken/en/resource-catalogue/oai-nb-no-sbr-85/) is a dataset with 24 hours of transcribed speech from podcasts and live events. The dataset contains a large amount of dialogues and unplanned speech, i.e., speech which is not read from a manuscript.
* [NB Uttale](https://www.nb.no/sprakbanken/en/resource-catalogue/oai-nb-no-sbr-79/) is a pronunciation lexicon with 785 000 words. Each word has an orthographic form in Norwegian Bokmål and phonemic transcriptions in 5 different dialects.

In addition to datasets developed during the project period, a number of older datasets are also important to the work in SCRIBE:
* [The NST ASR dataset](https://www.nb.no/sprakbanken/en/resource-catalogue/oai-nb-no-sbr-54/) consists of more than 500 hours of manuscript-read speech from around 1000 speakers. The dataset was developed by the firm Nordisk språkteknologi (NST) at the turn of the millenium and was later given to the Norwegian Language Bank after NST went bankrupt.
* [NB Tale](https://www.nb.no/sprakbanken/en/resource-catalogue/oai-nb-no-sbr-31/) is an acoustic-phonetic speech dataset for Norwegian. The database contains recordings of 380 speakers from 12 dialect aread as well as second language speakers with different native languages. The dataset is produced by Lingit AS for the Norwegian Language Bank. NB Samtale contains manuscript-read speech which is orthographically and phonetically transcribed. It also contains some unplanned speech, which is orthographically transcribed.
* [Rundkast](http://www.lrec-conf.org/proceedings/lrec2008/pdf/486_paper.pdf) is a 77 hours speech dataset consisting of orthographically transcribed speech from Norwegian radio broadcasts developed at NTNU. One hour is also transcribed phonetically. Rundkast is not publicly available.

# Open Models and Code (writing in progress)
We open-source models and code together with our publications. Below we list our main contributions in terms of models and code:
* From [*Improving Generalization of Norwegian ASR with Limited Linguistic Resources*; Per Erik Solberg, Pablo Ortiz, Phoebe Parsons, Torbjørn Svendsen, Giampiero Salvi (2023)](https://aclanthology.org/2023.nodalida-1.51/):
  * [SCRIBE HuggingFace](https://huggingface.co/scribe-project) contains several processed datasets and pre-trained models for speech recognition.
  * [Standardization of combined datasets for ASR](https://github.com/scribe-project/nodalida_2023_combined_training) contains the code for combining the open datasets used in the research, standardizing across them, and training (fine-tuning) wav2vec2 models on them.
* From [*BERT Attends the Conversation: Improving Low-Resource Conversational ASR*; Pablo Ortiz, Simen Burud (2021)](https://arxiv.org/pdf/2110.02267.pdf):
  * [Large-Scale Language Models for Conversational Speech Recognition](https://gitlab.com/sburud/master) contains code for implementing a BERT model that learns about conversational patterns and can be added as a module to ASR models to improve transcriptions.
