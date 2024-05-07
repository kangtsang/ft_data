---
license: other
library_name: peft
tags:
- llama-factory
- lora
- generated_from_trainer
base_model: /hy-tmp/chatglm3-6b/ZhipuAI/chatglm3-6b
model-index:
- name: glm3_train_keyword_2024-05-06
  results: []
---

<!-- This model card has been generated automatically according to the information the Trainer had access to. You
should probably proofread and complete it, then remove this comment. -->

# glm3_train_keyword_2024-05-06

This model is a fine-tuned version of [/hy-tmp/chatglm3-6b/ZhipuAI/chatglm3-6b](https://huggingface.co//hy-tmp/chatglm3-6b/ZhipuAI/chatglm3-6b) on the keyword dataset.

## Model description

More information needed

## Intended uses & limitations

More information needed

## Training and evaluation data

More information needed

## Training procedure

### Training hyperparameters

The following hyperparameters were used during training:
- learning_rate: 0.0005
- train_batch_size: 35
- eval_batch_size: 8
- seed: 42
- gradient_accumulation_steps: 8
- total_train_batch_size: 280
- optimizer: Adam with betas=(0.9,0.999) and epsilon=1e-08
- lr_scheduler_type: cosine
- num_epochs: 3.0
- mixed_precision_training: Native AMP

### Training results



### Framework versions

- PEFT 0.10.0
- Transformers 4.40.1
- Pytorch 2.2.1+cu121
- Datasets 2.18.0
- Tokenizers 0.19.1