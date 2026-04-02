MLOps
=====

Architecture
------------

- [Machine Learning: The High-Interest Credit Card of Technical Debt](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/43146.pdf)
- [Rules of Machine Learning: Best Practices for ML Engineering](https://developers.google.com/machine-learning/guides/rules-of-ml)
- [MLOps on Vertex AI - Google Cloud](https://cloud.google.com/vertex-ai/docs/start/introduction-mlops)

Experiment Tracking & Model Registries
---------------------------------------

- [MLflow](https://mlflow.org/) — Most widely adopted open-source experiment tracking, model registry, and deployment platform; industry standard
- [Weights & Biases (W&B)](https://wandb.ai/) — De facto standard for deep learning teams; best-in-class visualization, collaboration, and sweep-based hyperparameter tuning
- [DVC (Data Version Control)](https://dvc.org/) — Git-like versioning for datasets and models; pairs well with MLflow for full experiment reproducibility
- [ClearML](https://clear.ml/) — Open-source end-to-end MLOps platform with auto-logging; strong self-hosted option

Pipeline Orchestration
-----------------------

- [Apache Airflow](https://airflow.apache.org/) — Dominant workflow orchestration platform; widely used for ML and data pipelines; Airflow 3.0 expanded GenAI support
- [Kubeflow](https://www.kubeflow.org/) — Kubernetes-native ML workflow platform; developed by Google
- [Prefect](https://www.prefect.io/) — Python-native workflow orchestration; modern Airflow alternative with a strong developer experience
- [Dagster](https://dagster.io/) — Asset-centric pipelines with excellent data lineage tracking; widely adopted for production ML workflows
- [ZenML](https://www.zenml.io/) — ML-specific open-source framework that separates pipeline code from infrastructure; 50+ built-in stack connectors
- [Metaflow](https://metaflow.org/) — Netflix-originated; designed for data scientists who want seamless local-to-cloud parity
- [Flyte](https://flyte.org/) — Strongly typed, Kubernetes-native ML pipelines; used at Lyft and Spotify

LLM / GenAI Application Frameworks
------------------------------------

- [LangChain](https://www.langchain.com/) — Most widely adopted framework for building LLM applications, chains, and agents
- [LlamaIndex](https://www.llamaindex.ai/) — Leading framework for RAG (Retrieval-Augmented Generation) over custom data sources
- [Haystack](https://haystack.deepset.ai/) — Production-grade NLP/LLM pipeline framework; strong for search and document QA
- [LiteLLM](https://github.com/BerriAI/litellm) — OpenAI-compatible API gateway to 100+ LLMs; handles load balancing, fallbacks, and cost tracking

LLM Fine-Tuning
----------------

- [Hugging Face Transformers](https://huggingface.co/docs/transformers) — Central hub for pretrained models and fine-tuning; industry standard
- [PEFT - Parameter-Efficient Fine-Tuning](https://huggingface.co/docs/peft) — LoRA, QLoRA, and other efficient fine-tuning methods; dramatically reduces GPU requirements
- [TRL - Transformer Reinforcement Learning](https://huggingface.co/docs/trl) — SFT, RLHF, and DPO fine-tuning; increasingly the standard toolkit alongside PEFT
- [Unsloth](https://github.com/unslothai/unsloth) — 2–5× faster and more memory-efficient fine-tuning than vanilla PEFT
- [Axolotl](https://github.com/axolotl-org/axolotl) — Streamlined fine-tuning wrapper widely used in the open-source community

LLM Inference & Serving
------------------------

- [vLLM](https://github.com/vllm-project/vllm) — High-throughput LLM serving with PagedAttention; production standard for open-source LLM deployment
- [Ollama](https://ollama.com/) — Local LLM inference with a simple CLI; ideal for development and testing
- [llama.cpp](https://github.com/ggml-org/llama.cpp) — C/C++ LLM inference; foundational for edge and CPU inference; 73k+ GitHub stars
- [BentoML](https://www.bentoml.com/) — Framework-agnostic model packaging and microservice deployment
- [Ray Serve](https://docs.ray.io/en/latest/serve/index.html) — Scalable distributed model serving built on Ray
- [KServe](https://kserve.github.io/website/) — Kubernetes-native model serving; successor to KFServing

LLM Observability & Evaluation
--------------------------------

- [Langfuse](https://langfuse.com/) — Open-source LLM observability: tracing, evals, and prompt management
- [Arize AI / Phoenix](https://github.com/Arize-ai/phoenix) — Open-source LLM tracing and evaluation; hallucination detection; enterprise ML monitoring via Arize AI

Vector Databases
-----------------

- [Pinecone](https://www.pinecone.io/) — Managed vector DB; optimized for low-latency similarity search
- [Weaviate](https://weaviate.io/) — Open-source + managed; combines vector search with a knowledge graph layer
- [Qdrant](https://qdrant.tech/) — Open-source + managed; performance-focused, cost-efficient
- [Milvus](https://milvus.io/) — Open-source; designed for billion-vector scale
- [Chroma](https://www.trychroma.com/) — Lightweight open-source; best for prototyping and small apps
- [pgvector](https://github.com/pgvector/pgvector) — PostgreSQL extension for vector search; growing fast for teams already on Postgres

Feature Stores
---------------

- [Feast](https://feast.dev/) — Leading open-source feature store; modular, integrates with existing infrastructure
- [Tecton](https://www.tecton.ai/) — Enterprise managed feature platform; built by creators of Uber's Michelangelo
- [Hopsworks](https://www.hopsworks.ai/) — End-to-end feature and model management; strong in regulated industries

Python Libraries
----------------

- [PyTorch](https://pytorch.org/) — Dominant deep learning framework for research and production
- [scikit-learn](https://scikit-learn.org/) — The standard for classical ML; irreplaceable for tabular data workflows
- [Pandas](https://pandas.pydata.org/) — Foundation of data processing in Python; widely used for tabular data
- [Polars](https://pola.rs/) — High-performance DataFrame library; increasingly used for large datasets where Pandas is slow
- [spaCy](https://spacy.io/) — Industrial-strength NLP; production standard; integrates with LLMs via spacy-llm
- [Sentence Transformers](https://www.sbert.net/) — Embeddings for semantic search and RAG; extremely widely adopted
- [Gensim](https://radimrehurek.com/gensim/) — Topic modeling (LDA, Word2Vec); still best-in-class for unsupervised text analysis
- [NLTK](https://www.nltk.org/) — Natural language toolkit; used in education and research (not recommended for production)
- [Hugging Face Datasets](https://huggingface.co/docs/datasets) — Standard library for loading and sharing ML datasets
- [Accelerate](https://huggingface.co/docs/accelerate) — Hugging Face library for distributed training across hardware backends
- [Ray](https://www.ray.io/) — Distributed Python framework covering training, hyperparameter tuning, and serving

Data Annotation Tools
---------------------

- [Label Studio](https://labelstud.io/) — Widely adopted open-source annotation tool; covers text, images, audio, video, and LLM outputs
- [Argilla](https://argilla.io/) — Open-source (now part of Hugging Face); the leading tool for LLM dataset curation and RLHF preference data
- [Prodigy](https://prodi.gy/) — Active annotation tool with LLM integration; strong for human-in-the-loop workflows (v1.13+)
- [Datasaur](https://datasaur.ai/) — Annotation platform expanded to cover LLM use cases
- [doccano](https://github.com/doccano/doccano) — Open-source text annotation for NER, classification, and seq2seq
- [BRAT](https://brat.nlplab.org/) — Browser-based rapid annotation; widely cited in academic and biomedical NLP
- [Labelbox](https://labelbox.com/) — Comprehensive annotation platform with LLM fine-tuning workflow support
- [Encord](https://encord.com/) — Strong for multimodal annotation (vision + text) with active LLM support
- [Humanloop](https://humanloop.com/) — Pivoted to LLM evaluation and RLHF feedback platform; prompt management and evals

Data Annotation Services
------------------------

- [Scale AI](https://scale.com/) — Enterprise annotation and SFT/RLHF data service for GenAI
- [Amazon Mechanical Turk](https://www.mturk.com/) — Crowdsourced annotation; still operational but declining for AI-specific tasks
- [Google Cloud Data Labeling Service](https://cloud.google.com/vertex-ai/docs/datasets/data-labeling-job) — Now part of Vertex AI
- [Appen](https://www.appen.com/) — Managed annotation service with global workforce; covers data collection and labeling
