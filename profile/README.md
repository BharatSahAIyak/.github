# Bharat SahAIyak

<img width="1305" alt="BHASAI Arch" src="https://github.com/BharatSahAIyak/.github/assets/7413816/58724bdc-9a4c-4076-910a-457b80f008b8">


## Applications

### Apps, Copilots, Bots
- [KSAI](https://github.com/BharatSahAIyak/KISAI-bot)
- [BHASAI Admin](https://github.com/BharatSahAIyak/admin)

### UI Framework/Generator

- [App Framework - Stencil](https://github.com/SamagraX-Stencil/stencil-ui/)
- [Deployer Service](https://github.com/BharatSahAIyak/deployer)
- [Config Manager](https://github.com/BharatSahAIyak/deployer/tree/dev/src/modules/external-config)

### RLHF
- [v1 RFC - coming soon on Admin](https://github.com/BharatSahAIyak/ai-tools/issues/25) - Sprint 2411
- [Dictionary]()

## Recipes

### Recipe Runtime

- [Runtime](https://github.com/BharatSahAIyak/orchestrator)
- [State Machine Spec - XState](https://stately.ai/docs/xstate)
- [Logic Definition](https://github.com/BharatSahAIyak/orchestrator/blob/dev/src/xstate/xstate.factory.ts)

```
Generic Transformers
  Code Runner Transformer
  HTTP GET Transformer
  HTTP POST Transformer
  Field Setter Transformer
  LLM Transformer
  Neural Coreference Transformer
  SQL Query Builder Transformer
  Translate Transformer
If-Else Transformers
  Random Binary Transformer
  Doc Retriever Transformer
Retry Transformers
  Simple Retry Transformer
Switch-Case Transformers
  Label Classifier Transformer
State Restore Transformers
  User Feedback Loop Transformer
```

### Generative Recipe Agents
> Coming Soon

- [Existing Nodes](https://bharatsahaiyak-docs.vercel.app/developer_guide/guides/transformers/supported_transformers)

### Recipe Builder
- [Flowise UI](https://github.com/BharatSahAIyak/flowise)

## AI Models

### Foundational Models
- [Transformer Node](https://github.com/BharatSahAIyak/packages/tree/main/packages/transformers/src/modules/generic/llm)

### Domain and Task Models
| Model/Task                | Inference   |
|-------------------------------|---------|
| ASR                           | [MMS](https://github.com/BharatSahAIyak/ai-tools/tree/dev/src/asr/fairseq_mms) |
| ASR - ngram correction (agri-Odia)              | [KenLM](https://github.com/BharatSahAIyak/ai-tools/tree/dev/src/spell_check/kenlm/local) |
| Translate (Azure,GCP,Bhashini)  | [External services](https://github.com/BharatSahAIyak/ai-tools/tree/dev/src/text_translation/) | 
| Spell check (agri-Odia,English) | [symspell](https://github.com/BharatSahAIyak/spellcheck/blob/dev/spellcheck/app.py)| 
| Named Entity recognition (agri-English)              | [distilbert-finetuned](https://github.com/BharatSahAIyak/ai-tools/tree/dev/src/ner/agri_ner_akai)| 
| Embedding (agri finetuned)     | [Colbert](https://github.com/BharatSahAIyak/ai-tools/tree/dev/src/embeddings/colbert/local) | 
| Embedding (self-hosted)     | [bge](https://github.com/BharatSahAIyak/ai-tools/tree/dev/src/embeddings/bge-small/local), [instructor](https://github.com/BharatSahAIyak/ai-tools/tree/dev/src/embeddings/instructor)| 
| Embedding - OpenAI                         | [External Service](https://github.com/BharatSahAIyak/ai-tools/tree/dev/src/embeddings/openai)|
| Reranker  | [bge](https://github.com/BharatSahAIyak/ai-tools/tree/dev/src/rerankers/bge_base/local)| 
| Classifier | [BERT,mobileBERT,DeBERTa](https://github.com/BharatSahAIyak/ai-tools/tree/dev/src/text_classification) | 
Semantic chunking | [MPNet](https://github.com/BharatSahAIyak/ai-tools/tree/dev/src/chunking/MPNet/local) |
| Neural coreference | [FCoref](https://github.com/BharatSahAIyak/ai-tools/tree/dev/src/coref/fcoref) |
| Language detection | [Bhashini](https://github.com/BharatSahAIyak/ai-tools/tree/dev/src/text_lang_detection/bhashini/remote) | 

## Datasets

### I/O Plugins
- [Status Webhook Standards Spec](https://github.com/BharatSahAIyak/standards/issues/13)
- [YT Parser](https://github.com/BharatSahAIyak/yt-parser) | [PDF Parser](https://github.com/BharatSahAIyak/pdf-parser) | [Excel Parser](https://github.com/BharatSahAIyak/excel-parser)
- [Document Service](https://github.com/BharatSahAIyak/document-service)
- [Dataset Service](https://github.com/BharatSahAIyak/dataset-service)

### Dataset Builder Plugins
- [Syntheic Dataset Generation/Management](https://github.com/BharatSahAIyak/autotune)

### Knowledge Graphs
- [KG Generation through Semantic Text](https://github.com/BharatSahAIyak/knowledge-graph/tree/main-ts) | Coming Soon
- [KG Visualizer](https://github.com/BharatSahAIyak/kg-markdown-enhancer) | Coming Soon

## AIOps

### Training Pipeline

| Model/Task                | Training|
|-------------------------------|---------|
| ngram correction               | [KenLM](https://github.com/BharatSahAIyak/ai-tools/tree/dev/src/spell_check/kenlm/local) |
| spellcheck          | [spellcheck](https://github.com/BharatSahAIyak/spellcheck/blob/dev/spellcheck/app.py) |

### FineTuning Pipelines
| Model/Task                | Fine-tuning|
|-------------------------------|---------|
|  Named Entity recognition              | [distilBERT](https://github.com/BharatSahAIyak/NER_training) |
| Classification | [BERT based models](https://github.com/BharatSahAIyak/Classifier_training) |
| Embedding/Reranker | [ColBERT](https://github.com/BharatSahAIyak/colbert-finetune) |

- [Autotune (Sagemaker Alternative OS)](https://github.com/BharatSahAIyak/autotune) | Coming Soon

### Chip / GPU / PaaS API

- [Docker Installation](https://github.com/BharatSahAIyak/docker-bhasai)
- [Infra Setup - Terraform](https://github.com/BharatSahAIyak/infra)
- [GPU/CPU Split by the control plane](https://github.com/BharatSahAIyak/docker-bhasai/blob/dev/ai-tools/generate.sh) | [Config](https://github.com/BharatSahAIyak/ai-tools/blob/dev/config.json)
