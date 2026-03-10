# Telecom X – Parte 2: Prevendo Churn

## 🎯 Missão

A missão do desafio é desenvolver modelos preditivos capazes de prever quais clientes têm maior chance de cancelar seus serviços.

A empresa quer antecipar o problema da evasão, e cabe a você construir um pipeline robusto para essa etapa inicial de modelagem.

## 🧠 Objetivos do Desafio

    Preparar os dados para a modelagem (tratamento, encoding, normalização).

    Realizar análise de correlação e seleção de variáveis.

    Treinar dois ou mais modelos de classificação.

    Avaliar o desempenho dos modelos com métricas.

    Interpretar os resultados, incluindo a importância das variáveis.

    Criar uma conclusão estratégica apontando os principais fatores que influenciam a evasão.

## 🧰 O que foi praticado

✅ Pré-processamento de dados para Machine Learning

✅ Construção e avaliação de modelos preditivos

✅ Interpretação dos resultados e entrega de insights

✅ Comunicação técnica com foco estratégico

## 📊 Resultados dos modelos


| Modelo               | Accuracy | Precision (Sim) | Recall (Sim) | F1-score (Sim) | Precision (Não) | Recall (Não) | F1-score (Não) |
|----------------------|----------|-----------------|--------------|---------------|-----------------|--------------|---------------|
| Regressão Logística  | 0.80     | 0.65            | 0.52         | 0.58          | 0.84            | 0.90         | 0.87          |
| Random Forest        | 0.79     | 0.62            | 0.49         | 0.55          | 0.83            | 0.89         | 0.86          |
| Regressão Logística Balanceada             | 0.75     | 0.52            | 0.79         | 0.62          | 0.91            | 0.73         | 0.81          |

## 💡 Recomendações


- Fazer campanhas de incentivo à fidelidade nos primeiros meses
- Fazer descontos especiais para planos anuais
- Sugerir revisão de preços

## 🏁 Conclusão

A avaliação realizada permitiu identificar e aprofundar em circunstâncias claras associadas ao cancelamento de serviços, bem como validar modelos preditivos capazes de modelar as diferentes instâncias de desistência e insatisfação do usuário. Esses resultados permitem avaliar estratégias de retenção focadas em novos clientes, contratos flexíveis e serviços de valor agregado para cada um dos usuários, aplicando ações de atração além de sua fidelização.
