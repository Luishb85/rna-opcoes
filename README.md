# Rede Neural para Precificação de Opções (Modelo Black-Scholes)

Este projeto aplica uma Rede Neural Artificial (RNA) para aprender a precificar opções de compra (calls) com base no modelo Black-Scholes.

## 🧪 Tecnologias utilizadas
- Python
- Scikit-learn
- Matplotlib / Seaborn
- Numpy / Pandas

## 🎯 Objetivo
Avaliar a capacidade da RNA de replicar a fórmula do modelo Black-Scholes com base em:

- Moneyness (strike/spot)
- Volatilidade
- Tempo até o vencimento
- Taxa livre de risco

## 📊 Resultados
- RMSE: `4.5891e-05` (erro < 1%)
- Melhor desempenho entre modelos não lineares
- RNA replicando com precisão os preços da fórmula Black-Scholes

## 👨‍💻 Autor
Luis Henrique Balloni  
[LinkedIn](https://www.linkedin.com/in/luishenriqueballoni/)
