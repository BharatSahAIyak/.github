# Bharat SahAIyak

<img width="1304" alt="Screenshot 2024-05-14 at 9 56 15 PM" src="https://github.com/BharatSahAIyak/issues/assets/7413816/7ea7ce19-8e7e-405d-8220-42649c617c37">

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

## Recipe

### Recipe Runtime

- [Runtime](https://github.com/BharatSahAIyak/orchestrator)
- [State Machine Spec - XState](https://stately.ai/docs/xstate)
- [Logic Definition](https://github.com/BharatSahAIyak/orchestrator/blob/dev/src/xstate/xstate.factory.ts)

### Generative Recipe Agents
> Coming Soon

### Recipe Builder
- [Flowise UI](https://github.com/BharatSahAIyak/flowise)

## AI Models

### Foundational Models
- [Transformer Node]()

### Domain and Task Models
| Model/Task                | Inference   |
|-------------------------------|---------|
| ASR                           | [Self](https://github.com/BharatSahAIyak/ai-tools/tree/dev/src/asr/fairseq_mms) |
| ASR - ngram correction               | [Self](https://github.com/BharatSahAIyak/ai-tools/tree/dev/src/spell_check/kenlm/local) |
| Translate (Azure,GCP,Bhashini)  | [External service](https://github.com/BharatSahAIyak/ai-tools/tree/dev/src/text_translation/) | 
| Spell check | [Self](https://github.com/BharatSahAIyak/spellcheck/blob/dev/spellcheck/app.py)| 
| Named Entity recognition               | [Self](https://github.com/BharatSahAIyak/ai-tools/tree/dev/src/ner/agri_ner_akai)| 
| Embedding (self-hosted)     | [Colbert](https://github.com/BharatSahAIyak/ai-tools/tree/dev/src/embeddings/colbert/local) , [bge](https://github.com/BharatSahAIyak/ai-tools/tree/dev/src/embeddings/bge-small/local), [instructor](https://github.com/BharatSahAIyak/ai-tools/tree/dev/src/embeddings/instructor)| 
| Embedding - OpenAI                         | [External Service](https://github.com/BharatSahAIyak/ai-tools/tree/dev/src/embeddings/openai)|
| Reranker - bge                      | [Self](https://github.com/BharatSahAIyak/ai-tools/tree/dev/src/rerankers/bge_base/local)| 
| Classifier | [Self](https://github.com/BharatSahAIyak/ai-tools/tree/dev/src/text_classification) | 

## Datasets

### I/O Plugins
- [Status Webhook Standards Spec](https://github.com/BharatSahAIyak/standards/issues/13)
- [YT Parser](https://github.com/BharatSahAIyak/yt-parser) | [PDF Parser](https://github.com/BharatSahAIyak/pdf-parser) | [Excel Parser](https://github.com/BharatSahAIyak/excel-parser)

### Document Service

- [Document Service](https://github.com/BharatSahAIyak/document-service)

### Dataset Service

- [Dataset Service](https://github.com/BharatSahAIyak/dataset-service)

## AIOps

### Training Pipeline

### FineTuning Pipelines

### Chip / GPU / PaaS API

- [Docker Installation](https://github.com/BharatSahAIyak/docker-bhasai)
- [Infra Setup - Terraform](https://github.com/BharatSahAIyak/infra)
- [GPU/CPU Split by the control plane](https://github.com/BharatSahAIyak/docker-bhasai/blob/dev/ai-tools/generate.sh) | [Config](https://github.com/BharatSahAIyak/ai-tools/blob/dev/config.json)
