# E-ML-Project

README.txt file with lists of
– libraries/packages used
– online publicly-available repository code used or adapted
– code that you wrote

This is an example of what your README.txt file should look like.

Mention the external libraries your team used (e.g., numpy, sklearn, etc)

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

List the publicly available code(s) you used in your project. Please provide the URL for the code and mention if you modified the code or not. If you modified the code, please mention the number of lines your team modified or added.

### Publicly available codes used:

* None

List the code(s) written entirely by your team. Please mention roughly how many lines of code is present in each and provide a brief description (for each) of what the code does.

### Scripts/functions written by our team:

* **LLM_testing.ipynb** Initial experiments with LLMs. Zero-shot and few-shot prompting with Gemma-3-1B on 50-sample test subset (~100 lines)
* **LoRA_phishing.ipynb** QLoRA fine-tuning of Gemma-3-1B for phishing email classification, training loop, model evaluation with soft-probability scoring, and out-of-distribution dataset testing (~320 lines)
* **E-ML.ipynb** Data preprocessing, EDA, BoW and TF-IDF logistic regression baselines, Word2Vec + XGBoost classifier with hyperparameter tuning, and out-of-distribution evaluation on external datasets (~500 lines)
