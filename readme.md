# Case - IFood - Data Science | Data Analyst

#SantanderCoders2024 | ADA TECH | DS - Repositório referente ao Case IFood no Módulo 02, disciplina de Técnicas de Programação I, Instrutor Victor Brito

## Dinâmica

* O case realizado em duas fases: 
* Fase I - Entendimento do problema e planejamento;
    * Entendimento do Problema e Planejamento (Máximo de 25 min)
    * Baixar os arquivos na pasta da aula ou repositório
        * pdf: contém a descrição (em inglês) do case, seus objetivos e informações sobre os dados
        * csv: base de dados de referência para a realização do case
    * Construir um roteiro de análise (planejamento) para solução do problema, individualmente. O roteiro deve ser no formato de:
        * Tarefa: Descrição da tarefa
            * Subtarefa1: Descrição/Justificativa
            * Subtarefa2: Descrição/Justificativa

* Fase II - Execução.
    * Execução (1h:40min)
    * Cada aluno terá até 1h:40min para desenvolver a solução do case individualmente
    * Ao final do tempo (aprox. às 21h:15min), deverá  anexar sua solução no drive.

## Tarefas

Descrição: O objetivo é entender melhor o perfil desses consumidores, identificar padrões de comportamento e preferências de consumo, e, assim, derivar insights valiosos para futuras campanhas de marketing.

### Subtarefa 1 - Entendimento do Dataset

* Compreender o contexto geral dos dados.
* Identificar a unidade de análise (neste caso, cada linha representa um consumidor).

### Subtarefa 2 - Análise Exploratória dos Dados (EDA):

* Examinar as colunas presentes e o que cada uma representa.
* Verificar a consistência das informações (valores nulos, outliers, tipos de dados).

### Subtarefa 3 Derivação de Informações:

* Criar variáveis derivadas que possam enriquecer a análise (ex: perfil etário, média de gastos).
* Explorar correlações entre variáveis.

### Subtarefa 4 - Tratamento de Dados:
* Lidando com dados ausentes, outliers e normalização de variáveis.

### Subtarefa 5 - Storytelling e Comunicação dos Achados:
* Visualizar os insights chave utilizando gráficos.
* Preparar uma narrativa coerente que explique os principais resultados.

## Resultados
* 2014 é o ano considerado para a respectiva análise.
* Restaram outros métodos para tratar a base de dados para que a estatística seja melhor acurada.
* Após análise dos dados e a correlação entre possíveis variáveis, optou-se pela relação simples e inicial entre as colunas `Recency`, período em dias da compra mais recente, e `Age`, respectiva idade do consumidor.
* Foram acrescentadas as colunas `MntTotalSpend`, total de compras, e `MntMediaSpend`, valor médio de compras.
* Para facilitar as análises, foram agrupados `Recency_Group` e `Age_Group`. Assim, é possível estabelecer conjuntos de semlhenças do perfil do consumidor e a relação entre eles.
* Há um equilíbrio entre as faixas de renda (`Income`).
* A situação `Marital_Status` mais recorrente é `Married`.
* O nível educacional mais forte é `Graduation`.
* A faixa etária 41-60 foi a que mais comprou.
* A Faixa etária 60-80 foi a que mais gastou.
* Assim, conforme as análises pontuais, o perfil mais inclinado a participar da nova campanha é:
    * Idade média de 49 anos.
    * Ativo em compras entre 40 e 60 dias.
    * Casado
    * Com graduação
    