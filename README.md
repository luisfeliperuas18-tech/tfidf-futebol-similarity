Este repositório contém um projeto de Ciência de Dados que aplica o algoritmo TF-IDF (Term Frequency–Inverse Document Frequency) para transformar descrições textuais de jogadores de futebol em vetores numéricos, permitindo o cálculo de similaridade de cosseno entre os textos.

O objetivo principal é identificar quais jogadores possuem perfis semelhantes com base em sua descrição textual, utilizando técnicas de NLP (Processamento de Linguagem Natural) em Python.

📂 Conteúdo do Projeto

Notebook Jupyter (.ipynb) com o passo a passo da análise
Pré-processamento de texto com NLTK
Vetorização com TfidfVectorizer (Scikit-learn)
Cálculo da similaridade entre textos usando cosine similarity
Funções reutilizáveis para limpeza, tokenização e vetorização
Relatório técnico em PDF explicando metodologia e resultados

⚠️ IMPORTANTE – Sobre o Dataset

O notebook não contém o dataset incluído por padrão.
Para que o código funcione corretamente, o usuário deve fazer upload do arquivo CSV contendo as descrições dos jogadores.
❗ Sem o dataset, o código não irá executar corretamente.

🚀 Tecnologias Utilizadas

Biblioteca	          Uso
pandas	          leitura e manipulação do dataset
nltk	            limpeza de texto, stopwords, tokenização
scikit-learn	    TF-IDF e cálculo de similaridade
re	              remoção de pontuação e padrões textuais

📌 Como Executar o Projeto

Clone o repositório
Abra o notebook em Colab, Jupyter Notebook, Kaggle Notebook ou outro ambiente Python
Faça upload do dataset .csv antes de rodar as células
Execute o notebook de cima para baixo
