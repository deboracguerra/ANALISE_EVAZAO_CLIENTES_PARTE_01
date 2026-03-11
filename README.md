Projeto de Análise Exploratória de Dados (EDA) desenvolvido com o objetivo de investigar padrões associados à evasão de clientes (churn) na empresa fictícia TelecomX.

A análise busca identificar fatores que contribuem para o cancelamento de serviços e gerar insights estratégicos que possam apoiar decisões de retenção de clientes.

🎯 Objetivo do Projeto
O objetivo principal deste projeto é analisar o comportamento dos clientes da TelecomX e identificar variáveis que possam estar associadas à evasão de clientes.

A partir da análise dos dados, busca-se:

Identificar padrões de cancelamento
Investigar características dos clientes que evadem
Gerar insights estratégicos para retenção
Preparar os dados para modelos de Machine Learning
📂 Estrutura do Projeto
🧹 Preparação e Tratamento dos Dados
Antes da análise exploratória, foi realizada uma etapa de limpeza e preparação dos dados, incluindo:

🔹 Tratamento de valores inconsistentes
🔹 Conversão de tipos de dados
🔹 Padronização de variáveis
🔹 Tradução de nomes de colunas para Português
Também foi criada uma versão da base preparada para Machine Learning, na qual as variáveis categóricas foram transformadas utilizando a técnica de One-Hot Encoding, convertendo categorias em variáveis binárias (0 e 1).

🔎 Análise Exploratória dos Dados (EDA)
Durante a análise exploratória foram investigadas diversas dimensões dos dados, incluindo:

👤 Perfil Demográfico
Gênero
Senioridade
Clientes com parceiros
Clientes com dependentes
📄 Perfil Contratual
Tipo de contrato
Tempo de permanência do cliente
📡 Serviços Contratados
Internet (Fibra óptica / DSL)
Streaming de TV
Streaming de filmes
Suporte técnico
Segurança online
Backup online
Proteção do dispositivo
💳 Métodos de Pagamento
Cheque eletrônico
Cheque enviado por correio
Débito automático
Crédito automático
💰 Análise Financeira
Cobrança mensal
Cobrança total
Perdas financeiras associadas à evasão
🔗 Análise de Correlação
Foi construída uma matriz de correlação para identificar relações entre as variáveis e a evasão de clientes.

💡 Principais Insights
A análise revelou alguns padrões relevantes associados à evasão de clientes na TelecomX:

📉 Contratos mensais apresentam maior probabilidade de evasão.
💳 Clientes que utilizam cheque eletrônico estão mais presentes entre os cancelamentos.
👥 Clientes não idosos representam a maior parcela das evasões.
⏳ Os primeiros meses de contrato apresentam maior incidência de cancelamentos.
📡 Clientes com serviço de Fibra Óptica aparecem com maior frequência entre os registros de evasão.
Esses padrões ajudam a compreender melhor o comportamento dos clientes e os possíveis fatores associados ao churn.

📢 Recomendações Estratégicas
Com base nos insights identificados, algumas ações podem ser consideradas:

📅 Incentivar contratos de maior duração (anuais ou bienais).
💳 Estimular o uso de pagamentos automáticos.
🤝 Criar estratégias de retenção nos primeiros meses de contrato.
📡 Investigar possíveis problemas relacionados ao serviço de fibra óptica.
🤖 Utilizar modelos de Machine Learning para prever clientes com maior risco de evasão.
🛠️ Tecnologias Utilizadas
🐍 Python
📊 Pandas
📈 Matplotlib
🎨 Seaborn
📓 Jupyter Notebook
⚙️ Como Rodar o Projeto
Clonar o repositório:
git clone https://github.com/Lucas-matrixx/DataAnalysis_ChallengeAluraStore
Instruções de instalação
✔️ 1. Crie (ou ative) seu ambiente virtual no terminal seguindo uma das opções abaixo:

Windows - com Git bash
python -m venv venv
source ./venv/Scripts/activate
Windows - com PowerSheel
python -m venv venv
venv\Scripts\Activate.ps1
Linux/Mac
python3 -m venv venv
source venv/bin/activate
✔️ 2. Instale as dependências do requirements.txt

Com o ambiente ativo:

pip install -r requirements.txt
🚀 Próximos Passos
Este projeto representa a primeira etapa da análise de churn.

Os próximos passos incluem:

Construção de modelos preditivos de Machine Learning
Avaliação de modelos como:
Random Forest
KNN
Regressão Logística
Identificação das variáveis mais importantes para previsão de churn
