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


```
GPT-4 tiktoken token count:

          token_count
count  1000000.000000
mean      1197.179246
std        964.177338
min        513.000000
25%        653.000000
50%        871.000000
75%       1315.000000
max       8191.000000


Total count:	1197.18 M tokens
```