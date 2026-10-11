# 📉 Projeto: Análise de Cancelamento de Clientes (Churn)

Este é um projeto de Ciência de Dados focado em identificar os principais motivos de cancelamento em uma base com mais de 800 mil clientes e criar um modelo preditivo.

## 📋 Etapas do Pipeline Desenvolvido
1. **Definição do Problema e Seleção do Dataset:** Utilização de dados públicos reais de cancelamento hospedados no Kaggle.
2. **Análise Exploratória e Tratamento dos Dados (EDA):** Limpeza de valores nulos, remoção de colunas irrelevantes e criação de gráficos interativos com Plotly.
3. **Modelagem e Otimização:** Uso de Aprendizado Supervisionado (Classificação Binária) comparando Regressão Logística (Baseline) e Random Forest, com tratamento de variáveis de texto (Dummies) e Padronização Numérica (StandardScaler).
4. **Análise Crítica:** Diagnóstico prático para ações de negócio e tomada de decisões.

## 🛠️ Tecnologias Utilizadas
* Python
* Pandas
* Scikit-Learn
* Plotly / Matplotlib

## 📊 Principais Descobertas (Insights)
* **Contrato Mensal:** Clientes com contrato mensal possuem taxa de cancelamento crítica.
* **Suporte:** Clientes que ligam mais de 4 vezes para o Call Center tendem a cancelar.
* **Financeiro:** Atrasos no pagamento acima de 15 dias geram abandono do serviço.

* ### 3. O que aprendi de difícil no projeto?
* Como a base de dados é muito gigante (mais de 800 mil linhas), o meu computador não teve memória RAM suficiente na primeira tentativa e o VS Code chegou a travar (erro de falta de memória) e não conseguia salvar no GitHub
* Para resolver isso, tive que ajustar o código para criar um modelo mais "leve": reduzi a base de dados para 100.000 linhas e reduzir o número de teste de árvore de decisão

