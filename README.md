# 📊 Previsão de Encargos Médicos com Modelos de Regressão

Este projeto tem como objetivo prever os custos médicos individuais com base em características demográficas e comportamentais, utilizando modelos de regressão como **Regressão Linear**, **KNN** e **Árvore de Decisão**.

---

## 🧠 Tecnologias e Bibliotecas

- Python 3
- Pandas
- Matplotlib, Seaborn
- Scikit-learn

---

## 📁 Estrutura do Projeto

- `IADT - Fase 1 - Tech Challenge.ipynb` — Colab Notebook com todo o código, visualizações e análise.
- `README.md` — este arquivo.
- Dados carregados diretamente via Parquet do [Hugging Face](https://huggingface.co/datasets/rahulvyasm/medical_insurance_data).

---

## 🎯 Objetivos

- Analisar fatores que influenciam os custos médicos.
- Explorar os dados com estatísticas descritivas e visualizações.
- Construir e comparar modelos de regressão.
- Avaliar o desempenho dos modelos com métricas como MAE, MSE e R².

---

## 🔍 Principais Resultados

- **Variável mais relevante:** `fumante_yes` teve a maior correlação com os custos.
- **Melhor modelo:** Árvore de Decisão, com R² = 0.87 e MAE = R$ 2.814.
- Modelos foram avaliados com métricas e gráficos comparando valores reais e previstos.

---

## 📈 Visualizações

- Histogramas
- Mapas de calor de correlação
- Pairplot por categoria de fumante
- Gráfico de dispersão: valores reais vs. predições

---

## ✅ Conclusão

A **Árvore de Decisão** foi o modelo mais preciso para prever encargos médicos e se mostrou eficaz para identificar padrões não lineares nos dados.  
Esse modelo pode ser útil em cenários reais como **precificação de seguros**, **triagem de risco** e **análise de saúde populacional**.

---

📚 Projeto desenvolvido como parte da **Fase 1 do curso IA para Devs pela FIAP**.
