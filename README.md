---
library_name: transformers
base_model: gpt-2
tags:
- generated_from_trainer
model-index:
- name: ioi--elr-llr-relr-rllr-es-
  results: []
---

<!-- This model card has been generated automatically according to the information the Trainer had access to. You
should probably proofread and complete it, then remove this comment. -->

# ioi--elr-llr-relr-rllr-es-

This model is a fine-tuned version of [gpt-2](https://huggingface.co/gpt-2) on an unknown dataset.

## Model description

More information needed

## Intended uses & limitations

More information needed

## Training and evaluation data

More information needed

## Training procedure

### Training hyperparameters

The following hyperparameters were used during training:
- learning_rate: 5e-05
- train_batch_size: 8
- eval_batch_size: 8
- seed: 42
- optimizer: Use adamw_torch with betas=(0.9,0.999) and epsilon=1e-08 and optimizer_args=No additional optimizer arguments
- lr_scheduler_type: linear
- num_epochs: 3.0

### Framework versions

- Transformers 4.47.1
- Pytorch 2.5.1
- Datasets 3.2.0
- Tokenizers 0.21.0
