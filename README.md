# 📊 Análise de Attrition da IBM

Análise exploratória de dados sobre **“employee attrition”** (rotatividade de funcionários) da IBM, com foco em entender fatores que influenciam a permanência ou saída dos colaboradores.

---

## 📋 Sumário

- [Contexto & Objetivo](#contexto--objetivo)  
- [📚 Bibliotecas Utilizadas](#bibliotecas-utilizadas)  
- [📂 Estrutura do Projeto](#estrutura-do-projeto)  
- [🛠️ Instalação & Execução](#instalação--execução)  
- [🔍 Metodologia & Análise](#metodologia--análise)  
- [📈 Resultados & Insights](#resultados--insights)  
- [🧠 Conclusões](#conclusões)  
- [👤 Autor](#autor)  
- [🤝 Contribuições](#contribuições)  

---

## Contexto & Objetivo

Este projeto utiliza a base de dados "WA_Fn-UseC-Employee-Attrition" do Kaggle para:

1. Explorar estatísticas básicas e distribuição de dados sobre funcionários da IBM.  
2. Entender quais atributos (idade, salário, tempo de empresa, satisfação, entre outros) estão relacionados ao turnover.  
3. Realizar visualizações para comunicar padrões de forma clara.

---

## 📚 Bibliotecas Utilizadas

- `pandas`, `numpy` – manipulação e estatísticas.  
- `matplotlib`, `seaborn` – visualizações como histogramas, boxplots e heatmaps.  

---

## 📂 Estrutura do Projeto

- `IBM - Projeto pandas - Estudo.ipynb` – notebook com toda análise exploratória.  
- `employee_attrition.csv` – base de dados original do Kaggle.  
- `.gitignore`, `.gitattributes` – configuração de projeto.

---

## 🛠️ Instalação & Execução

Pré-requisitos: Python 3.6+, Jupyter Notebook.

```bash
git clone https://github.com/PedroSilva0z/Analise_IBM.git
cd Analise_IBM
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook "IBM - Projeto pandas - Estudo.ipynb"
```
---

## 🔍 Metodologia & Análise

  1. Importação e inspeção inicial com df.head(), df.info(), df.describe().
  2. Limpeza de dados, se necessário (remover nulos, corrigir tipos).
  3. Análise univariada: distribuição de idade, salário, tempo de empresa, taxa de saída.
  4. Comparações entre grupos (Attrition = Yes/No): boxplots, contagens e percentuais.
  5. Heatmap de correlação para identificar relações relevantes.
  6. (Opcional) Clusterização ou modelagem para aprofundar entendimento dos perfis que saem.

---

## 📈 Resultados & Insights

- Distribuição de idade e salário entre colaboradores que saem ou ficam.
- Identificação de possíveis fatores (ex: satisfação no trabalho, horas extras) que influenciam a saída.
- Correlações visuais através de heatmap entre variáveis numéricas e Attrition.
- Perfis de colaboradores com maior tendência a deixar a empresa.

---

## 🧠 Conclusões

- A rotatividade está associada a fatores como satisfação, tempo de empresa e carga horária.
- Funcionários com menor satisfação e maior carga horária têm tendência maior a sair.
- Correlações ajudam a identificar variáveis-chave para retenção.

--- 

## 👤 Autor

Pedro Silveira - Projeto do curso Hashtag

📍 São Paulo, Brasil

🔗 LinkedIn

--- 

## 🤝 Contribuições
Contribuições são bem-vindas!
Abra uma issue ou envie um pull request com sugestões, melhorias ou novas análises.
