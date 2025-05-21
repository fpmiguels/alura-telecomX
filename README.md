Análise de Evasão de Clientes (Churn)

Este projeto tem como objetivo analisar dados de clientes de uma empresa de telecomunicações, com foco em identificar padrões que levam ao cancelamento do serviço (churn). A análise busca entender o comportamento dos clientes e propor ações para reduzir a evasão.

📊 Objetivos

Identificar os principais fatores que influenciam o cancelamento dos clientes.

Realizar um processo completo de ETL: extração, tratamento e análise dos dados.

Gerar visualizações e insights relevantes para tomada de decisão.

Propor recomendações para retenção de clientes.

🧹 Etapas Realizadas

1. Extração e Limpeza de Dados

Os dados foram extraídos de uma API hospedada no GitHub.

Colunas foram padronizadas, tipos corrigidos e valores ausentes tratados.

Valores da coluna Charges.Total foram convertidos para numérico.

2. Análise Exploratória de Dados (EDA)

Visualização das proporções de churn.

Comparação do churn com variáveis como tipo de contrato, serviços contratados, gastos e tempo de permanência.

Geração de gráficos (barras, violinplots, countplots) com Seaborn e Matplotlib.

3. Principais Insights

Clientes com contrato mensal (month-to-month) cancelam mais.

Clientes com menor gasto total (até R$ 500) apresentaram maior evasão.

Clientes com fibra óptica tendem a cancelar mais do que os com DSL.

Clientes sem serviços adicionais, como:

Backup online;

Proteção de dispositivos;

Suporte técnico (TechSupport);

apresentam taxa de churn mais alta.

4. Correlação

Análise de correlação com Churn mostra que:

Tempo de permanência (tenure) tem forte correlação negativa com churn.

Menor número de serviços contratados está associado à maior evasão.

💡 Recomendações

Criar programas de fidelização para contratos mensais.

Incentivar adesão a serviços adicionais (backup, suporte, proteção).

Monitorar clientes com menor gasto e com poucos serviços.

Atuar nos primeiros meses de contrato, onde a evasão é maior.

🛠️ Tecnologias Utilizadas
Python (Pandas, NumPy, Seaborn, Matplotlib)

Jupyter Notebook

API REST (para extração dos dados)

📁 Estrutura do Projeto

📦 projeto-churn/
├── 📄 README.md
├── 📊 Churn_Analysis.ipynb
└── 📁 dados/
    └── dados_extraidos.json

👨‍💻 Autor
Felipe Miguel
