# Sentimental Analysis Using BERT
Training Bert on word-level tokens for masked language Modeling

**Steps**

**1)** Run sentiment-analysis-using-bert-mixed-export.ipynb 
```
'''Experimental Parameters'''

epochs=1
max_position_embeddings_=12
min_seq_length=3
hidden_size_=282
num_attention_heads_=6
num_hidden_layers_=4
type_vocab_size_=1
batch_size_=64
top_n=10
path = "vocab.txt"

```


**Requirments**


```
python = 3.8.3
transformers==4.5.0
tokenizers==0.10.3
pytorch==1.10.2
numpy==1.23.3
pandas==1.1.5
```
