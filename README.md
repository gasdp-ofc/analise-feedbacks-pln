# 📊 Análise Inteligente de Feedbacks de Clientes com PLN

Este projeto aplica técnicas de **Processamento de Linguagem Natural (PLN)** para analisar feedbacks de clientes de um e-commerce, transformando textos não estruturados em **insights estratégicos** para apoio à tomada de decisão.

A solução considera desafios reais do português brasileiro, como linguagem informal, variações regionais e grande volume de dados textuais.

---

## 🎯 Objetivo do Projeto

Demonstrar, na prática, como técnicas modernas de PLN podem ser utilizadas para:
- Identificar sentimentos dos clientes
- Descobrir padrões e temas recorrentes
- Agrupar feedbacks semanticamente semelhantes
- Apoiar decisões estratégicas baseadas em dados

---

## 🧠 Técnicas Utilizadas

- Limpeza e normalização de textos
- Tokenização
- Remoção de stopwords
- Stemming e lematização
- Vetorização com **TF-IDF**
- Representação semântica com **Word2Vec**
- Classificação de sentimentos (Machine Learning)
- Descoberta de tópicos com **LDA**
- Clusterização com **K-Means**
- Visualização de dados com gráficos

---

## 🛠️ Tecnologias e Bibliotecas

- Python  
- NLTK  
- spaCy (Português)  
- Scikit-learn  
- Gensim  
- Matplotlib  
- Google Colab  

---

## 📂 Estrutura do Repositório

📁 analise-feedbacks-pln
├── analise_feedbacks_pln.ipynb
├── README.md


---

## ▶️ Como Executar

### Opção 1 — Google Colab (Recomendado)
1. Abra o notebook no Google Colab  
2. Execute as células em ordem  
3. Visualize os outputs, gráficos e relatórios  

### Opção 2 — Localmente
```bash
pip install nltk spacy gensim scikit-learn matplotlib
python -m spacy download pt_core_news_sm

📈 Resultados Gerados

Classificação automática de sentimentos (positivo, negativo e neutro)

Tópicos recorrentes identificados automaticamente

Agrupamento semântico de feedbacks

Gráficos para apoio visual à análise

Esses resultados permitem compreender rapidamente a percepção dos clientes e identificar pontos de melhoria.

🧪 Dataset

Os dados utilizados neste projeto são simulados, representando feedbacks reais de clientes, conforme permitido no desafio acadêmico.

📚 Fundamentação Teórica

CATARINO, M. H. Redes Neurais. Freitas Bastos, 2025.

ESPOSITO, F. Programação de Grandes Modelos de Linguagem. Pearson, 2025.

CRUZ, L.; ALENCAR, A.; SCHMITZ, E. Assistentes Virtuais Inteligentes e Chatbots. Brasport, 2019.

👨‍💻 Autor

Guilherme Alves
Estudante de Gestão de TI
Interesse em Dados, Inteligência Artificial e Tecnologia

🚀 Considerações Finais

Este projeto demonstra como a Inteligência Artificial pode ser aplicada para transformar grandes volumes de texto em conhecimento estratégico, aproximando empresas das reais necessidades e percepções de seus clientes.


---

## ⭐ EXTRA

### 🔹 Commits sugeridos
- `feat: implementa preprocessamento de texto`
- `feat: analise de sentimentos com ML`
- `feat: descoberta de topicos com LDA`
- `docs: adiciona documentacao no README`


Estudante de Gestão de TI | PLN | Dados | IA aplicada a problemas reais
