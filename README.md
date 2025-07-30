# 📊 Análise de Rotatividade de Clientes - TelecomX-Parte 2

Este projeto tem como objetivo analisar a rotatividade de clientes (churn) da empresa fictícia **TelecomX**. Utilizando dados sobre o perfil e comportamento dos clientes, o projeto busca identificar os principais fatores que influenciam na saída de clientes da empresa, além de construir modelos preditivos para antecipar essa rotatividade.

## 🧾 Descrição dos Dados

O conjunto de dados contém informações de clientes, incluindo:

- `ID_Cliente`: Identificador único do cliente
- `Rotatividade`: Indicador de churn (1 = saiu, 0 = permaneceu)
- `Sexo_Cliente`, `Cliente_Idoso`, `Cliente_Parceiro`, `Cliente_Dependentes`: Dados demográficos
- `Tempo_Servico`: Quantidade de meses como cliente
- `Servico_Telefone`, `Multiplas_Linhas`, `Servico_Internet`: Tipo de serviços contratados
- Serviços adicionais: `Seguranca_Online`, `Backup_Online`, `Protecao_Dispositivo`, `Suporte_Tecnico`, `Streaming_TV`, `Streaming_Filmes`
- `Contrato_Conta`: Tipo de contrato (mensal, anual, etc.)
- `Conta_Digital`: Se utiliza conta digital
- `Metodo_Pagamento`: Forma de pagamento
- `Encargos_Mensais`, `Encargos_Totais`, `Contas_Diarias`: Valores relacionados a pagamento

## 🛠️ Tecnologias Utilizadas

- Python 3
- Pandas e NumPy para manipulação de dados
- Matplotlib e Seaborn para visualização
- Scikit-learn para modelagem preditiva
- Jupyter Notebook para análise exploratória

## 🎯 Objetivos

1. Análise exploratória de dados (EDA)
2. Identificação de padrões de rotatividade
3. Pré-processamento dos dados
4. Construção e avaliação de modelos preditivos (como árvore de decisão, random forest, etc.)
5. Geração de insights para retenção de clientes

## 📈 Resultados Esperados

- Relatório de métricas de desempenho dos modelos
- Visualizações que ajudam a entender os principais fatores de churn
- Recomendações para redução da rotatividade

## 🚀 Como Executar

1. Clone este repositório
2. Instale as dependências com `pip install -r requirements.txt`
3. Execute os notebooks na pasta `/notebooks` para ver a análise e os modelos

## 🧠 Contribuições Futuras

- Implementação de um dashboard com Streamlit
- Integração com dados em tempo real
- Aplicação de técnicas de aprendizado não supervisionado

