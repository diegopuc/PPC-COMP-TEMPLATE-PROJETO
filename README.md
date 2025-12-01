# 📌 Projeto de Análise Estatística e Aplicação de Modelo de Machine Learning

Descreva brevemente o objetivo do seu projeto.  
Explique qual problema o dataset escolhido permite investigar e qual modelo de aprendizado de máquina foi utilizado.

Inclua imagens, figuras, gráficos exploratórios ou prints se desejar.

---

## 👥 Integrantes

- Nome 1 — RA: XXXXXXXX  
- Nome 2 — RA: XXXXXXXX  
- Nome 3 — RA: XXXXXXXX  

---

## 🔗 Dataset Utilizado

Informe os dados essenciais sobre o conjunto de dados escolhido.

- **Nome do dataset:**  
- **Link (Kaggle ou outra fonte):**  
- **Descrição do dataset:** número de amostras, variáveis, tipo de problema, etc.  
- **Variável-alvo (target):**  
- **Justificativa da escolha:** por que este dataset é adequado para o modelo escolhido?  

---

## 🧠 Modelo de Aprendizagem de Máquina

### Modelo escolhido:
Exemplos:
- Regressão Linear  
- Regressão Logística  
- KNN  
- Árvore de Decisão  
- Random Forest  
- Naive Bayes  

Explique:
- O que o modelo faz  
- Por que ele foi escolhido para este dataset  
- Como ele funciona de maneira simples (explicação intuitiva)

---

## 📊 Análise Exploratória dos Dados (EDA)

Inclua:

- Estatísticas descritivas (média, mediana, mínimo, máximo, desvio padrão, etc.)  
- Gráficos relevantes:  
  - histogramas  
  - boxplots
  - etc 
- Identificação e comentário sobre padrões encontrados  
- Identificação de outliers quando relevante  

---

## 🧪 Treinamento e Testes do Modelo

Insira aqui o código ou prints do notebook.  
O código **deve** estar acessível de uma das formas:

- **Link para notebook no Google Colab (obrigatoriamente compartilhado como visualização):**  
  `https://colab.research.google.com/...`

ou

- **Código Python dentro da pasta `/src/` do repositório**

### Passos obrigatórios no notebook:
- Limpeza e preparação dos dados  
- Tratamento de valores ausentes  
- Codificação de variáveis categóricas (OneHotEncoder)  
- Padronização quando necessário (StandardScaler)  
- Separação treino/teste  
- Treinamento do modelo  
- Previsões  
- Avaliação das métricas  

---

## 📐 Métricas de Avaliação

### **Para Classificação**
- Accuracy  
- Matriz de confusão  
- Precision e Recall (explicação simples e intuitiva)

---

### **Para Regressão**

#### **1. MAE (Mean Absolute Error)**  
Erro Absoluto Médio.  
Mostra, em média, **quanto o modelo erra em valor absoluto**.  
É fácil de interpretar.  
Quanto menor o MAE, melhor.

#### **2. RMSE (Root Mean Squared Error)**  
Raiz do Erro Quadrático Médio.  
Penaliza erros maiores de forma mais forte.  
Útil quando você quer evitar erros grandes.  
Quanto menor, melhor.

#### **3. R² (Coeficiente de Determinação)**  
Mostra **quanta variação dos dados o modelo consegue explicar**.  

Interpretação rápida:  
- **R² = 1.0** -> o modelo explica 100% da variação  
- **R² = 0.0** -> o modelo não explica nada  
- **R² negativo** -> o modelo é pior que adivinhar pela média  

---

## 🧬 Experimentos Realizados

Descreva pelo menos 3 experimentos feitos pelo grupo, por exemplo:

- Alterar profundidade da Decision Tree  
- Comparar K=3, K=5 e K=7 no KNN  
- Comparar dados normalizados vs. não normalizados  
- Remover ou adicionar variáveis  
- Testar diferentes tamanhos de treino/teste  

Inclua:

- Código  
- Gráficos ou tabelas  
- Interpretação do que mudou e por que mudou  

---

## 📈 Resultados Obtidos

Resumo das principais descobertas:

- Como o modelo se saiu?  
- Quais variáveis têm maior influência?  
- Houve overfitting ou underfitting?  
- O modelo faz sentido para esse dataset?  

Inclua tabelas e gráficos relevantes.

---

## 🧩 Conclusões Finais

- O que aprenderam sobre o modelo escolhido?  
- O que descobriram sobre o dataset?  
- O que poderia ser feito para melhorar o modelo?  
- O modelo é adequado para esse tipo de dado?  

---

## 📁 Organização do Repositório

```
📦 projeto-datascience/
 ┣ 📂 src/
 ┃ ┗ model.ipynb           # notebook principal
 ┣ 📂 docs/
 ┃ ┗ imagens-graficos/
 ┣ README.md               # este arquivo
```

---

## 📝 Entrega

📅 **Data de entrega: 16/12/2025**  
🧾 **Formato obrigatório:**  
- PDF  
- Notebook  
- README preenchido  
🎯 **Notebook deve estar acessível com permissão de visualização**

---

## 📝 Licença

Este projeto está licenciado sob MIT ou outro modelo escolhido pelo grupo.
