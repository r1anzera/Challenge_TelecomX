## 📊 TelecomX: Análise de Evasão de Clientes (Churn)
Este projeto tem como objetivo analisar o comportamento dos clientes da TelecomX para identificar padrões que levam ao cancelamento de serviços (Churn). A análise utiliza técnicas de Ciência de Dados para extrair insights valiosos que possam auxiliar na retenção de clientes.

---


## 📋 Estrutura do Projeto
O projeto está dividido nas seguintes etapas fundamentais:

1. Extração: Carregamento dos dados a partir de uma fonte remota em formato JSON.

2. Transformação (Limpeza e Tratamento): Normalização de dados aninhados e tratamento de inconsistências.

3. Análise Exploratória (EDA): Visualização de dados para identificar correlações e comportamentos.

4. Conclusões e Insights: Resumo dos achados estatísticos.

---

## 🛠️ Tecnologias Utilizadas
As seguintes bibliotecas de Python foram fundamentais para este estudo:

1. Pandas: Para manipulação e análise de dados estruturados.

2. JSON: Para processamento da fonte de dados original.

3. Matplotlib & Seaborn: Para a criação de visualizações e gráficos estatísticos.

4. Numpy & Math: Para operações matemáticas e tratamento de matrizes.

---

## 📈 Principais Insights
A análise revelou padrões críticos sobre a evasão:

1. Risco Inicial: Clientes com pouco tempo de contrato (tenure) apresentam maior probabilidade de desistência.

2. Tipo de Contrato: Contratos do tipo "mês a mês" são os mais instáveis, enquanto contratos anuais favorecem a retenção.

3. Métodos de Pagamento: Clientes que utilizam métodos manuais (como cheque eletrónico) têm taxas de churn superiores aos que utilizam pagamentos automáticos.