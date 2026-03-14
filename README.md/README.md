# German Credit Risk Analysis

Projeto de análise de risco de crédito utilizando o dataset Statlog German Credit.

## Objetivo
Explorar dados de crédito e construir um modelo simples de classificação para prever risco de inadimplência.

## Ferramentas
- Python
- Pandas
- Scikit-Learn
- Power BI

## Estrutura do Projeto

data/
- raw → dados brutos
- processed → dados tratados

notebooks/
- análises exploratórias

scripts/
- scripts Python

dashboard/
- arquivo Power BI

## Principais Resultados

Neste projeto foi desenvolvido um modelo de classificação de risco de crédito utilizando o German Credit Dataset.

Foram testados dois algoritmos de Machine Learning:
- Regressão Logística
- Random Forest

O modelo de Regressão Logística apresentou o melhor desempenho, alcançando:

- Accuracy: 79%
- Recall da classe inadimplente: 54%

O recall da classe inadimplente é uma métrica importante em modelos de crédito, pois indica a capacidade do modelo em identificar clientes com maior risco de não pagamento.

Durante a análise, algumas variáveis se destacaram como fatores relevantes para o risco de crédito, entre elas:

- Valor do empréstimo (credit_amount)
- Prazo do empréstimo em meses (duration_months)
- Taxa de comprometimento da renda com a parcela (installment_rate)
- Idade do cliente (age)

Os resultados sugerem que valores de crédito mais altos, prazos mais longos e maior comprometimento da renda estão associados a um aumento do risco de inadimplência.

Além da modelagem preditiva, foi desenvolvido um dashboard no Power BI para exploração visual dos dados e análise do perfil de risco dos clientes.