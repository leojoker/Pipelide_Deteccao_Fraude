# 🛡️ Fraud Detection Pipeline – Power BI + Python

[![Python](https://img.shields.io/badge/Python-3.11-blue)](https://www.python.org)
[![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow)]()
[![License](https://img.shields.io/badge/license-MIT-green.svg)]()

Este projeto implementa uma pipeline completa para detecção de fraudes utilizando Python, Machine Learning e visualização com Power BI. Os dados são simulados com base em cenários reais de transações suspeitas e previsões são feitas com base em um modelo Random Forest.

---

## 📂 Estrutura do Projeto

```
fraud-detection-pipeline/
├── data/
│   ├── raw/                # dados_coletados.csv
│   ├── new/                # novos_dados.csv
│   └── output/             # previsoes_fraude.xlsx (gerado)
├── models/
│   └── modelo_treinado_fraude.pk
├── dashboard/
│   └── analise_risco.pbix
├── notebooks/
│   └── DeployProducao.ipynb
├── src/
│   ├── gerar_modelo.py
│   └── gerar_previsoes.py
├── requirements.txt
├── .gitignore
└── README.md
```

---

## 🚀 Como Executar

### 1. Treinar o modelo
```bash
python src/gerar_modelo.py
```

### 2. Gerar previsões com novos dados
```bash
python src/gerar_previsoes.py
```

### 3. Abrir o dashboard Power BI
Abra `dashboard/analise_risco.pbix` no Power BI Desktop.

---

## 📊 Tecnologias Utilizadas

- Python 3.11
- Pandas, Scikit-learn, Joblib
- Power BI Desktop
- Jupyter Notebook

---

## 📌 Autor

**Leonardo Barbosa**  
Cientista de Dados com foco em soluções aplicadas a risco, prevenção de fraudes e inteligência analítica.  
📫 [linkedin.com/in/leonardo-barbosa](https://www.linkedin.com/in/leonardo-barbosa777/))

---

## 📝 Licença

MIT – Sinta-se livre para usar e adaptar este projeto.
