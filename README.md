# E-Saude-Curitiba

Dados disponíveis em: https://www.curitiba.pr.gov.br/dadosabertos/busca/


Este código está lendo um arquivo csv com dados de atendimento médico e realizando algumas etapas de limpeza, processamento e análise de dados utilizando as bibliotecas Pandas, Matplotlib e Datetime.

Aqui estão os principais passos:

Lendo o arquivo csv utilizando a função read_csv do Pandas e definindo o separador como ponto e vírgula e a codificação como ANSI.
Convertendo a coluna 'Data do Atendimento' para o formato datetime e criando colunas separadas para data e hora.
Convertendo a coluna 'Data de Nascimento' para o formato datetime e calculando a idade de cada paciente em anos.
Criando um novo DataFrame contendo apenas as colunas relevantes para análise.
Selecionando apenas as linhas com 'Tipo de Unidade' igual a 'UPA' e 'BASICO' e criando DataFrames separados para cada tipo de unidade.
Criando um gráfico de barras das 10 unidades com mais atendimentos no DataFrame 'UPA'.
Criando um gráfico de barras dos 10 códigos CID mais comuns no DataFrame 'UPA'.
Calculando a porcentagem de atendimentos que resultaram em internações no DataFrame 'UPA'.
Criando uma tabela dos 10 códigos CID que resultaram em internações no DataFrame 'UPA'.
Criando uma tabela dos atendimentos totais por unidade no DataFrame 'BASICO' e selecionando as 10 unidades com mais atendimentos.
Criando um gráfico de barras das 10 unidades com mais atendimentos no DataFrame 'BASICO'.


#################################


This code is reading a csv file with medical attendance data and performing some data cleaning, processing and analysis on it using Pandas, Matplotlib and Datetime libraries.

Here are the main steps:

Reading the csv file using Pandas' read_csv function and setting the separator to semicolon and the encoding to ANSI.
Converting the 'Data do Atendimento' column to datetime format and creating separate columns for date and time.
Converting the 'Data de Nascimento' column to datetime format and calculating the age of each patient in years.
Creating a new DataFrame containing only the relevant columns for analysis.
Selecting only the rows with 'Tipo de Unidade' equal to 'UPA' and 'BASICO' and creating separate DataFrames for each type of unit.
Creating a bar plot of the top 10 units with the most attendances in the 'UPA' DataFrame.
Creating a bar plot of the top 10 CID codes in the 'UPA' DataFrame.
Calculating the percentage of attendances that resulted in hospitalizations in the 'UPA' DataFrame.
Creating a table of the top 10 CID codes that resulted in hospitalizations in the 'UPA' DataFrame.
Creating a table of the total attendances per unit in the 'BASICO' DataFrame and selecting the top 10 units with the most attendances.
Creating a bar plot of the top 10 units with the most attendances in the 'BASICO' DataFrame.
