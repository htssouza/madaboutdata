Datasets
========

Dataset Collections
-------------------

- [ArXiv Data](http://arxiv.org/help/bulk_data)
- [Awesome Public Datasets](https://github.com/awesomedata/awesome-public-datasets)
- [CMU Statlib](http://lib.stat.cmu.edu/datasets/)
- [Data Hub](https://datahub.io/collections)
- [Gene expression omnibus](http://www.ncbi.nlm.nih.gov/geo/)
- [Google Research](https://datasetsearch.research.google.com/)
- [Interesting Datasets](https://github.com/curran/data)
- [Jeff Hammerbacher's Quota Introduction to Data Science: Data Sets](http://www.quora.com/Jeff-Hammerbacher/Introduction-to-Data-Science-Data-Sets)
- [Johns Hopkins Data Services](https://archive.data.jhu.edu/)
- [Kaggle Datasets](https://www.kaggle.com/datasets)
- [KDD Nugets Datasets](http://www.kdnuggets.com/datasets/index.html)
- [Public Data Sets on Amazon Web Services](http://aws.amazon.com/publicdatasets/)
- [Registry of Research Data Repository](https://www.re3data.org/)
- [Stanford Large Network Data](http://snap.stanford.edu/data/)
- [The University of Sheffield Research Data Repositories](https://www.sheffield.ac.uk/library/rdm/repositories)
- [UCI Machine Learning](http://archive.ics.uci.edu/ml/)

Healthcare Datasets
-------------------

- [Centers for Disease Control and Prevention](https://www.cdc.gov/)
- [HCUP: Datasets from US hospitals](https://hcup-us.ahrq.gov/databases.jsp)
- [ELVIRA Biomedical Data Set Repository](http://leo.ugr.es/elvira/DBCRepository/)
- [Informatics for Integrating Biology & The Bedside](https://www.i2b2.org/NLP/DataSets/)
- [Medicare](https://data.medicare.gov/data)
- [PubMed](https://pubmed.ncbi.nlm.nih.gov/)
- [RxNorm](https://www.nlm.nih.gov/research/umls/rxnorm/index.html) 
  See also https://www.phactmi.org/ and https://dailymed.nlm.nih.gov/dailymed/.
- [The NCBI Disease Corpus](https://www.ncbi.nlm.nih.gov/CBBresearch/Dogan/DISEASE/)
- [World Health Organization](https://apps.who.int/gho/data)

Healthcare Imaging Datasets
---------------------------

- [CT Medical Images](https://www.kaggle.com/kmader/siim-medical-images)
- [Medical Image Datasets](https://grand-challenge.org/challenges/)
- [OASIS - Open Access Series of Imaging Studies](http://www.oasis-brains.org/)
- [OpenfMRI - MRI](https://openfmri.org/)

Medical Speech Datasets
-----------------------

- [Medical Speech, Transcription, and Intent](https://www.kaggle.com/paultimothymooney/medical-speech-transcription-and-intent)
- [Medical Speech, Transcription, and Intent (English)](https://appen.com/datasets/audio-recording-and-transcription-for-medical-scenarios/)
- [Physician Dictation Audio & Transcribed Reports](https://www.ezdi.com/open-datasets/)

NLP Conversational Datasets
---------------------------

- [MultiWOZ - A Large-Scale Multi-Domain Wizard-of-Oz Dataset for Task-Oriented Dialogue Modelling](https://www.aclweb.org/anthology/D18-1547/)
- [The Pile - An 800GB Dataset of Diverse Text for Language Modeling](https://pile.eleuther.ai/)

LLM & Generative AI Datasets
-----------------------------

### Dataset Hubs

- [Hugging Face Datasets Hub](https://huggingface.co/datasets) - The largest hub of ready-to-use datasets for AI models, hosting over 600,000 public datasets across NLP, computer vision, audio, and more. Integrates with the `datasets` library for single-line loading and streaming.

### LLM Pretraining Corpora

- [RedPajama-Data-V2](https://huggingface.co/datasets/togethercomputer/RedPajama-Data-V2) - A 30-trillion-token open web dataset from Together AI, sourced from 84 Common Crawl dumps across five languages (English, French, Spanish, German, Italian), with 40+ quality annotations precomputed.
- [Dolma](https://allenai.github.io/dolma/) - A 3-trillion-token open corpus from Allen Institute for AI (AI2), mixing web content, academic publications, code, books, and encyclopedic materials. Used to train the OLMo family of open language models. Licensed under ODC-BY.
- [FineWeb](https://huggingface.co/datasets/HuggingFaceFW/fineweb) - A 15-trillion-token dataset from Hugging Face derived from 96 Common Crawl snapshots with aggressive quality filtering. FineWeb-Edu (1.3T tokens) is a high-quality educational subset that significantly outperforms other open pretraining corpora on knowledge benchmarks.

### Instruction Tuning & RLHF Datasets

- [Databricks Dolly 15k](https://huggingface.co/datasets/databricks/databricks-dolly-15k) - 15,000 human-written instruction-response pairs authored by over 5,000 Databricks employees. One of the first commercially permissive (CC BY-SA) instruction datasets covering Q&A, summarization, brainstorming, classification, and creative writing.
- [OpenAssistant Conversations (OASST)](https://huggingface.co/datasets/OpenAssistant/oasst1) - 161,443 human-annotated messages in 35 languages organized into 10,000+ conversation trees, with 461,292 quality ratings. A large-scale, human-crafted multilingual assistant dialogue corpus for RLHF and SFT.
- [LLMDataHub](https://github.com/Zjh-819/LLMDataHub) - A curated, community-maintained catalog of datasets for LLM training (pretraining, SFT, RLHF/DPO), with metadata on size, language, license, and usage for each entry.

### LLM Evaluation Benchmarks

- [MMLU (Massive Multitask Language Understanding)](https://huggingface.co/datasets/cais/mmlu) - 57-subject multiple-choice benchmark spanning STEM, humanities, and social sciences at high-school-to-professional difficulty. The standard general-knowledge evaluation benchmark; MMLU-Pro (12,000 harder questions, 10-choice) was introduced as models began saturating the original.
- [HumanEval](https://huggingface.co/datasets/openai/openai_humaneval) - OpenAI's 164-problem coding benchmark measuring functional correctness of code generated from docstrings. A primary standard for evaluating code generation and reasoning capabilities of LLMs.

### Multimodal Datasets

- [LAION-5B](https://laion.ai/blog/laion-5b/) - 5.85 billion CLIP-filtered image-text pairs (2.32B in English), enabling open replication of models like CLIP, GLIDE, and Stable Diffusion. One of the largest open multimodal datasets ever released.
- [DataComp](https://github.com/mlfoundations/datacomp) - A benchmark and dataset suite (2023) for studying how to build better multimodal training sets, providing CommonPool (12.8B image-text pairs from Common Crawl) alongside filtering and mixing baselines.

Open Government Sites
---------------------

- United Nations [http://data.un.org/](http://data.un.org/)
- U.S. [http://www.data.gov/](http://www.data.gov/)
  - [List of cities/states with open data](http://simplystatistics.org/2012/01/02/list-of-cities-states-with-open-data-help-me-find/)
- United Kingdom [http://data.gov.uk/](http://data.gov.uk/)
- France [http://www.data.gouv.fr/](http://www.data.gouv.fr/)
- Ghana [http://data.gov.gh/](http://data.gov.gh/)
- Australia [http://data.gov.au/](http://data.gov.au/)
- Germany [https://www.govdata.de/](https://www.govdata.de/) 
- Hong Kong [http://www.gov.hk/en/theme/psi/datasets/](http://www.gov.hk/en/theme/psi/datasets/)
- Japan [http://www.data.go.jp/](http://www.data.go.jp/)
- Many more [http://www.data.gov/opendatasites](http://www.data.gov/opendatasites)

Brazil Datasets
---------------

- DOU:
  - http://pesquisa.in.gov.br
- IBGE
  - http://dados.gov.br
  - https://sidra.ibge.gov.br/home/
  - http://www.portaltransparencia.gov.br
  - https://www2.camara.leg.br/orcamento-da-uniao
  - https://www.tesourotransparente.gov.br/ckan/dataset/lista-de-orgaos-do-siafi

- BCB
  - https://olinda.bcb.gov.br
  - https://sisweb.tesouro.gov.br

- CGU
  - http://www.cgu.gov.br/
  - http://www.unesco.org/new/pt/brasilia/about-this-office/unesco-resources-in-brazil/statistics/
  - https://www.investidor.gov.br/menu/Investidor_Estrangeiro/DadosEstatisticosEconomicosBrasil.html
