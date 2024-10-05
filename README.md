# Naive Bayes
![image](https://github.com/user-attachments/assets/0e8d999c-4d9b-474a-ac3d-b0722380327e)


## O que é?
- O Teorema de Bayes utiliza probabilidade para prever a categoria de uma amostra de dados
- Naive Bayes é tanto um conceito estatístico quanto o nome de um algoritmo que utiliza esses conceitos para a resolução de problemas usando uma base de dados histórica para gerar uma tabela de probabilidades que define qual a maior possiblidade de acerto de categorizar uma série de dados em uma classe
## Como funciona
- Gere as probalidades da categoria selecionada com probabilidades apriori e posteriori
- Monte uma tabela definindo a probabilidade em cima das definições já feitas em relação ao espaço amostral do dataset (probabilidades prévias)
- Faz a probabilidade de fazer parte de cada uma das categorias (probabilidades condicionais)
- As probabilidades com maiores valores serão as que irão definir se é da classe ou não
- Define que todas as variáveis preditoras são idependente uma das outras
### Exemplo
- Junto a esse reporitório tem um arquivo gerado no ambiente do Google Colab que trata de aplicar o algoritmo de naive bayes em 3 datasets:
  - risco_credito.csv
  - credit.pkl
  - census.pkl
## Aplicações
