# Challenge-Telecom-X
Challenge Telecom X análise de evasão de clientes
 Visão Geral do Projeto
Este projeto consiste na Análise de Evasão de Clientes (Churn) para a Telecom X, utilizando um conjunto de dados fornecido no contexto de um desafio. O objetivo principal é identificar os fatores que mais contribuem para a desistência de clientes e construir um modelo preditivo para antecipar quais clientes têm maior probabilidade de deixar a empresa.
As descobertas e o modelo servirão de base para a criação de estratégias de retenção mais eficazes e direcionadas.
________________________________________
💾 Conjunto de Dados
O dataset principal utilizado é o Challenge Telecom X. Ele contém informações detalhadas sobre os clientes, seus serviços contratados, dados demográficos e status de permanência na empresa.
Coluna Exemplo	Descrição Exemplo
customerID	Identificador único do cliente.
gender	Gênero do cliente.
tenure	Meses que o cliente permaneceu na empresa.
MonthlyCharges	Custo mensal total de todos os serviços do cliente.
Churn	Variável alvo: Sim (Evasão) ou Não (Permanece).
________________________________________
🛠️ Estrutura do Repositório
•	README.md: Este arquivo.
•	Challenge_Telecom_X_Analise_Evasao.ipynb: O notebook principal que contém todas as etapas da análise, desde a exploração inicial até a construção e avaliação do modelo.
•	data/: Pasta contendo o conjunto de dados original (e quaisquer arquivos de dados intermediários ou limpos, se aplicável).
o	telecom_churn.csv (Exemplo)
•	notebooks/: Pasta para notebooks de exploração preliminar ou testes (se houver).
•	assets/: Pasta para armazenar visualizações, gráficos e relatórios gerados.
________________________________________
🔬 Metodologia de Análise
A análise seguiu os seguintes passos principais:
1.	Exploração e Limpeza de Dados (EDA):
o	Verificação de valores ausentes e tratamento (se necessário).
o	Análise estatística descritiva das variáveis.
o	Identificação de outliers.
2.	Análise Descritiva e Visualizações:
o	Cálculo da Taxa de Churn geral.
o	Visualização da distribuição das variáveis e suas relações com a variável Churn.
o	Identificação dos principais drivers de Churn (ex: tipo de contrato, encargos mensais, serviços específicos, tempo de permanência).
3.	Pré-processamento de Dados para Modelagem:
o	Codificação (Encoding) de variáveis categóricas (One-Hot Encoding, Label Encoding).
o	Escalonamento de variáveis numéricas.
o	Divisão do conjunto de dados em treino e teste.
4.	Modelagem Preditiva:
o	Treinamento de um ou mais modelos de classificação (ex: Regressão Logística, Random Forest, Gradient Boosting).
o	Ajuste de hiperparâmetros (se necessário).
5.	Avaliação do Modelo:
o	Utilização de métricas como Acurácia, Precisão, Recall, F1-Score e Curva ROC/AUC.
o	Interpretação da Importância de Variáveis (Feature Importance) do modelo final para validar os drivers de churn.
________________________________________
💻 Como Executar
Para rodar a análise, siga os passos abaixo:
1.	Pré-requisitos: Certifique-se de ter o Python 3 instalado.
2.	Ambiente: É altamente recomendado criar um ambiente virtual (ex: conda create -n telecom_x python=3.x).
3.	Instalar Dependências: Instale as bibliotecas necessárias. As principais são:
Bash
pip install pandas numpy scikit-learn matplotlib seaborn
4.	Execução: Abra o notebook Challenge_Telecom_X_Analise_Evasao.ipynb em um ambiente Jupyter (Jupyter Notebook, JupyterLab ou VS Code) e execute as células sequencialmente.
________________________________________
💡 Principais Insights (Resumo Executivo)
(Esta seção seria preenchida após a execução da análise, mas um exemplo seria:)
•	A taxa geral de evasão (Churn Rate) é de aproximadamente 26,5%.
•	Clientes com contrato mês a mês e clientes sem segurança online ou backup são os mais propensos a evadir.
•	As cobranças mensais mais altas e o tempo de permanência (tenure) curto são as variáveis numéricas mais impactantes.
________________________________________
🤝 Contato

Autor: Anderson Carmona Data: Novembro de 2025


