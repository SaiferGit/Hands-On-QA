# Welcome to Hands on QA framework

---

## About this project

---

We explored recent studies in Question Answering System. Then tried out 3 different models for the sake of learning. Our steps were:

1. Firstly, we studied recent works on QA. More precisely, we studied Zylich et al.'s ``Exploring Automated Question Answering Methods for Teaching Assistance``which is published in AIE conf. in 2020 [Link](https://link.springer.com/chapter/10.1007/978-3-030-52237-7_49). The summary of the paper is uploaded [here](https://github.com/SaiferGit/Hands-On-QA/blob/main/qa-for-ta%20(Summery).pdf).

2. After that, we studied about `BERT`, what is the input-output format of it and how it works in case of QA. Then, tried out pretrained & fine-tuned `BERT` model. This `BERT` model is fine-tuned using [SQuAD v1.1 dataset](https://rajpurkar.github.io/SQuAD-explorer/explore/1.1/dev/). Then viewed our output.

  - Our used model was [bert-large-uncased-whole-word-masking-finetuned-squad](https://huggingface.co/bert-large-uncased-whole-word-masking-finetuned-squad?fbclid=IwAR0ahQVEOYymV9bbiIss2nsCJh6BXyMXAOyZERjrVXiyUL1RN1txftWYlhU)
  - [BERT paper](https://arxiv.org/abs/1810.04805)

3. Next, we studied about `DistilBERT`, which is a distiled version of `BERT`. It is more smaller, faster, cheaper and lighter than `BERT`. It doesn't have token ids like `BERT`, as a result is gives 70% more faster output than `BERT`. Gives almost accurate result like `BERT`. Our used model is pretrained and fined-tuned with same dataset as `BERT` was. Then we compared the output with `BERT` and verify the output.

  - [DistilBERT paper](https://arxiv.org/abs/1910.01108)
  - [distilbert-base-uncased-distilled-squad](https://huggingface.co/distilbert-base-uncased-distilled-squad)
  - [Huggingface All Pretrained Model List](https://huggingface.co/transformers/pretrained_models.html)
  - All functions of DistilBERT is mentioned [here](https://huggingface.co/transformers/model_doc/distilbert.html)

4. Lastly, we wanted to use a `DistilBERT` pretrained model and fine-tuned it with a custom dataset [SQuAD v2.0 trained dataset](https://rajpurkar.github.io/SQuAD-explorer/dataset/train-v2.0.json). Then tested our pretrained model with [SQuAD v2.0 dev dataset](https://rajpurkar.github.io/SQuAD-explorer/dataset/dev-v2.0.json) and checked accuracy of the model.

  - [Huggingface Documentation for Fine-tuning with Custom Datasets](https://huggingface.co/transformers/custom_datasets.html?fbclid=IwAR0HHEEUFfsT9wUkTb-l_nYTxfH2Twq0j99NDfw0WdhEAkgq7NFx_U7eTbQ)

### Contributors

- [Munshi Saif](www.github.com/SaiferGit)
- [Tazkia Altaaf](www.github.com/Tajkia05)
