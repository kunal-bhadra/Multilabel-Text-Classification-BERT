
# Classifying Multi-label texts with fine-tuned BERT & PyTorch Lightning

I have classified multi-label texts from a [Kaggle Competition](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge) with PyTorch Lightning. This was done with the **BERT-base** model from the HuggingFace Transformers library and fine-tuned on the above dataset with Lightning.


## 🚀 The Result

BERT-base model fine-tuned on our custom dataset giving an average *F1-score of 0.70*. We know this is due to the model making mistakes on the tags with low samples.


## ✏ Tech Stack for Project Development

- Python
- 🤗 Transformers
- PyTorch Lightning
- Pandas
- NumPy
- Sklearn


## 🧠 Approach taken
1. Tokenized text (with BERT tokenizer) and created PyTorch dataset
2. **Fine-tune BERT model with PyTorch Lightning**
3. Made predictions using the fine-tuned BERT model
4. Evaluate the performance of the model for each class 


## 🔗 Connect with me:
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://www.polywork.com/kunal_bhadra)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kunal-bhadra-cs/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/kunal_kaun)