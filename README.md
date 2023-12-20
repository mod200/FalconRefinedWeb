---
dataset_info:
  features:
  - name: text
    dtype: string
  splits:
  - name: train
    num_bytes: 5454844691
    num_examples: 1000000
  download_size: 3344664045
  dataset_size: 5454844691
configs:
- config_name: default
  data_files:
  - split: train
    path: data/train-*
source_datasets: tiiuae/falcon-refinedweb
language:
- en
license: odc-by
task_categories:
- text-generation
---

# BEE-spoke-data/falcon-refinedweb-1M_en_medium


A sample from [falcon-refinedweb](https://huggingface.co/datasets/tiiuae/falcon-refinedweb):

- more than 512 & less than 8192 gpt4 tiktoken tokens
- `en` only (via fasttext-langdetect)
- 1M samples