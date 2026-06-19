# 🐍 GCP FinOps Python Automation - Engenharia de Dados Avançada

Neste repositório, catalogo a minha biblioteca de scripts e notebooks em Python desenvolvidos diretamente no **Google Colab**, focados em automatizar rotinas analíticas, ingestão de dados e governança financeira integrada nativamente ao **Google BigQuery**.

## 📊 O Papel do Python na Governança
Enquanto o SQL atua processando grandes volumetrias de dados (*Big Data*) dentro do BigQuery, utilizo o Python como a camada inteligente de automação corporativa, permitindo disparar pipelines programáticos e gerar entregáveis prontos para as áreas de negócios.

## 📁 Catálogo de Automações

### ⚙️ 1. Execução Programática e Relatórios de Terminal
*   `relatorio_autonomo_custos_acima_da_media.py`: **Pedido do Gestor:** Criar um script automatizado que realize a autenticação via Client Library, execute a query analítica de subquery de forma transparente e formate os indicadores diretamente no console.

### 📊 2. Manipulação de DataSets e Geração de Arquivos Corporativos
<img width="1919" height="1038" alt="image" src="https://github.com/user-attachments/assets/1ed6192c-4d38-4a95-b498-0c9d73461b81" />

*   `extracao_bigquery_para_pandas_dataframe_csv.py`: **Pedido do Gestor:** Disponibilizar um extrator automatizado focado no time financeiro. O script converte o resultado do BigQuery em uma estrutura bidimensional utilizando a biblioteca **Pandas** (`.to_dataframe()`), trata o arquivo aplicando o separador nacional brasileiro (`sep=';'`) e codificação `utf-8-sig`, exportando nativamente para uma planilha Excel/CSV totalmente formatada em colunas.

### 🚨 3. Governança Baseada em Regras de Negócio com Pandas
<img width="1920" height="1042" alt="image" src="https://github.com/user-attachments/assets/bc621710-7ae1-4a56-95d0-beaa0ea04339" />


*   `classificacao_alertas_custo_pandas_dataframe.py`: **Pedido do Gestor:** Implementar uma camada de inteligência e rotulagem de forma autônoma no Python antes da exportação. O script avalia a matriz tridimensional, cria a coluna de governança `status_orcamento` mapeando recursos acima de R$ 400.00 como `🔴 CRÍTICO` e os demais como `🟢 DENTRO DO ESPERADO`, entregando um relatório totalmente tratado para o Excel.


## 🧠 Evolução Profissional
Dominar a integração de APIs do Google Cloud com engenharia estruturada em Python e Pandas consolida a minha capacidade técnica para construir pipelines eficientes de dados orientados a resultados de mercado.

