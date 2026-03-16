# E-ML-Project

### Libraries used:

* numpy
* pandas
* matplotlib
* scikit-learn
* torch
* transformers
* datasets
* evaluate
* tqdm
* nltk
* gensim
* scipy
* xgboost
* peft
* huggingface_hub
* requests
* google.colab
* bitsandbytes
* accelerate
* re
* logging
* typing
* os
* evaluate
* pathlib

### Publicly available codes used:

* None

### Scripts/functions written by our team:

* **LLM_testing.ipynb** Initial experiments with LLMs. Zero-shot and few-shot prompting with Gemma-3-1B on 50-sample test subset (~100 lines)
* **LoRA_phishing.ipynb** QLoRA fine-tuning of Gemma-3-1B for phishing email classification, training loop, model evaluation with soft-probability scoring, and out-of-distribution dataset testing (~320 lines)
* **E-ML.ipynb** Data preprocessing, EDA, BoW and TF-IDF logistic regression baselines, Word2Vec + XGBoost classifier with hyperparameter tuning, and out-of-distribution evaluation on external datasets (~500 lines)
* **bert.pynb** Frozen BERT embeddings with logistic regression baseline, fine-tuned BERT for binary classification with hyperparameter search, and validation evaluation (~360 lines)
* **fine_tuned_bert.ipynb** Loading fine-tuned BERT model, test set evaluation, and out-of-distribution dataset testing (~259 lines)
