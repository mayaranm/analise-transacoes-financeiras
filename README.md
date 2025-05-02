# 📊 Análise de Transações Financeiras

Projeto pessoal desenvolvido para praticar análise exploratória de dados com Python. O foco foi entender padrões de valor e risco em transações financeiras, a partir de uma base simulada.

---

## 🎯 Objetivo do Projeto

A ideia foi ir além da visualização: classificar as transações por nível de risco, gerar insights a partir dos dados e criar gráficos que facilitem a interpretação para outras pessoas — como analistas, gestores ou área de compliance.

---

## ✅ O que foi feito

- Limpeza e padronização dos dados
- Criação de uma **classificação de risco por valor**
- Geração de gráficos de apoio à análise
- Exportação das tabelas e gráficos para uma estrutura organizada de projeto

---

## 🛡️ Regras para Classificação de Risco

A nova coluna `risco` foi criada com base no valor da transação:

- Até R$500 → **baixo**
- De R$501 até R$2000 → **médio**
- Acima de R$2000 → **alto**

---

## 📊 Gráficos Criados

**1. Distribuição das transações por nível de risco**  
Gráfico de barras mostrando onde está a concentração dos registros.

**2. Boxplot dos valores por risco**  
Mostra a variação e os outliers em cada faixa de risco.

**3. Barras empilhadas por faixa de valor e risco**  
Cruza o valor das transações com o nível de risco atribuído.

---

## 🔎 Principais Insights

- A maior parte das transações está concentrada no risco **baixo**, o que é comum em bases de varejo ou serviços básicos.
- Transações de **alto valor** são poucas, mas têm variação muito grande, o que pode indicar comportamento atípico ou clientes com perfis bem diferentes.
- A combinação de faixa de valor + risco permite pensar em segmentações, limites ou regras de alerta.

---

## ⚙️ Tecnologias Utilizadas

- Python
- Pandas
- Seaborn e Matplotlib
- Ambiente: Spyder (Anaconda)

---

## 🚀 Possíveis Evoluções

- Criar alertas para transações fora do padrão
- Aplicar alguma técnica de clusterização para segmentar clientes
- Automatizar relatórios com Streamlit ou Jupyter

---

> Projeto criado por [Mayara N. Martins] com foco em aprendizado prático e análise aplicada.
