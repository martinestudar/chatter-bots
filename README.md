<img width="640" height="174" alt="image" src="https://github.com/user-attachments/assets/4a2fe28f-6019-471b-b4e8-4ab799f0c6bb" /># chatter-bots
Exercício de ChatterBots

Nomes: Pedro Martin, Alexandre Andrade e Lucas Barth

Todos os códigos foram usados e testados no google colab

Link do ex 4: https://colab.research.google.com/drive/17n7zB6TZ0zPYCFFEkDDTWrUuXqG26R2g?usp=sharing

#EX 1
### Dependências
- Python 3.x
- Bibliotecas padrão: `re`, `random`, `difflib`

Instalação (não requer pacotes adicionais):
```python
import re
import random
from difflib import get_close_matches









#EX 2

### Dependências
Python 3.x
json, random, re
nltk
scikit-learn
numpy

Instalação:

pip install nltk scikit-learn numpy


Baixar recursos do NLTK:

import nltk
nltk.download('movie_reviews')
nltk.download('punkt')
nltk.download('stopwords')

Imports
import json
import random
import re
import nltk
from nltk.corpus import movie_reviews
from nltk.tokenize import word_tokenize
from nltk.corpus import stopwords
from sklearn.feature_extraction.text import TfidfVectorizer
from sklearn.metrics.pairwise import cosine_similarity
import numpy as np








#EX 3

Dependências

Python 3.x

datasets==2.19.1

transformers

sentencepiece

scikit-learn

torch

tqdm

Instalação:

pip install datasets==2.19.1 transformers sentencepiece scikit-learn torch tqdm

Imports
from datasets import load_dataset
from sklearn.feature_extraction.text import TfidfVectorizer
from sklearn.neighbors import NearestNeighbors
from transformers import AutoModelForCausalLM, AutoTokenizer
import torch









#EX 4

Dependências

Python 3.x

datasets==2.19.1

transformers

sentencepiece

scikit-learn

torch

tqdm

Instalação:

pip install datasets==2.19.1 transformers sentencepiece scikit-learn torch tqdm

Imports
from datasets import load_dataset
from sklearn.feature_extraction.text import TfidfVectorizer
from sklearn.neighbors import NearestNeighbors
from transformers import AutoTokenizer, AutoModelForCausalLM
import torch








