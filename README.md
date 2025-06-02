# desafio-telecom
# Análise de Evasão de Clientes (Churn) - Jupyter Notebook

## 📄 Descrição

Este notebook apresenta uma análise exploratória de dados (EDA) focada em entender os fatores que influenciam a evasão de clientes (churn) em um serviço baseado em assinaturas. Através de visualizações e tratamento adequado dos dados, o notebook visa gerar insights para orientar estratégias de retenção.

---

## 🎯 Objetivo

- Investigar padrões relacionados à evasão dos clientes.
- Analisar variáveis categóricas e numéricas que impactam o churn.
- Fornecer recomendações baseadas nos dados para reduzir a taxa de evasão.

---

## 🧹 Etapas de Pré-processamento

- Conversão da coluna `Evasao` para tipo numérico (0 = Não evadiu, 1 = Evadiu).
- Tratamento e limpeza de colunas numéricas importantes (`account_Charges.Total`, `customer_tenure`).
- Remoção de registros com dados faltantes nas variáveis-chave para garantir a qualidade da análise.

---

## 🔍 Análise Exploratória de Dados (EDA)

- Visualização da distribuição geral da evasão.
- Análise da evasão em relação a variáveis categóricas como gênero, tipo de contrato e método de pagamento.
- Exploração da evasão baseada em variáveis numéricas, como o tempo de contrato e valor total gasto.

---

## 📊 Resultados e Insights

- Clientes com menor tempo de contrato apresentam maior propensão à evasão.
- Contratos mensais possuem taxas de churn mais altas que contratos trimestrais ou anuais.
- Pagamentos automáticos reduzem significativamente a evasão.
- Clientes que evadem tendem a ter menor gasto total, indicando possível desengajamento.

---

## 💡 Recomendações

1. Focar em melhorar a experiência dos clientes nos primeiros meses.
2. Incentivar planos com duração mais longa por meio de vantagens e descontos.
3. Promover métodos de pagamento automáticos para facilitar a continuidade.
4. Monitorar clientes de baixo gasto e pouco tempo para ações preventivas.

---

## 🔧 Tecnologias e Bibliotecas Utilizadas

- Python 3.x
- Pandas
- Seaborn
- Matplotlib

---

## 🚀 Próximos Passos

- Desenvolvimento de modelos preditivos de churn com machine learning.
- Testes A/B para validar intervenções e medir impacto em retenção.

---

## 📥 Como usar este notebook

1. Carregue o dataset com as informações dos clientes.
2. Execute as células sequencialmente para seguir o fluxo de limpeza, análise e visualização.
3. Utilize os insights gerados para direcionar estratégias de negócio.

---
