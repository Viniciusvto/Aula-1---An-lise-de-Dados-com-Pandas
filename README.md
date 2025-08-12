# Analise-de-Dados-com-Pandas e Python
**Aula 01:**

Criação de DataFrames: Vimos como criar um DataFrame a partir de dados estruturados, como listas e dicionários.
Leitura de Dados: Aprendemos a carregar dados de arquivos CSV para um DataFrame.
Exploração de Dados: Utilizamos métodos como head(), tail(), e info() para explorar a estrutura e o conteúdo dos dados.

**Aula 02:**

Limpeza de Dados: A aula focou na importância de tratar dados faltantes e como isso é crucial para a análise de dados.
Identificação de Dados Faltantes: Usamos o método isnull() para identificar valores nulos em um DataFrame e sum() para contar quantos valores nulos existem em cada coluna.
Tratamento de Dados Faltantes: Aprendemos três estratégias principais para lidar com dados faltantes:
Preenchimento: Usamos fillna() para preencher valores nulos com a média ou mediana dos dados.
Remoção: Utilizamos dropna() para remover linhas que contêm valores nulos.
Preenchimento com valor fixo: Substituímos valores nulos por um texto, como "Não informado".
Alteração de Tipos de Dados: Vimos como usar o método astype() para converter o tipo de dados de uma coluna, por exemplo, de float para int.



**Aula 03:**

Eu utilizei a biblioteca Pandas para plotar gráficos simples, como gráficos de barras, e contar a frequência de categorias usando a função value_counts(). Em seguida, explorei bibliotecas mais avançadas, como Seaborn e Matplotlib, que permitem uma maior personalização dos gráficos.
Aprendi a criar gráficos de barras para visualizar a distribuição de salários por nível de senioridade e a utilizar histogramas para entender a distribuição salarial. Também trabalhei com boxplots para visualizar a mediana, os quartis e os outliers dos dados salariais.
Por fim, tive uma introdução à biblioteca Plotly, com a qual criei gráficos interativos, como gráficos de pizza e de rosca, permitindo uma análise mais dinâmica dos dados. Como desafio, desenvolvi uma visualização do salário médio por país para o cargo de cientista de dados, utilizando o Plotly.





**Aula 04:** 

Instalação de Bibliotecas: Instalamos as bibliotecas necessárias, como Pandas, Plotly e Streamlit, utilizando um arquivo de requisitos.
Desenvolvimento do Dashboard:
Importação das bibliotecas e configuração do layout da página.
Carregamento de dados de um arquivo disponível no GitHub.
Criação de filtros dinâmicos na barra lateral para permitir a exploração dos dados em tempo real.
Adição de métricas principais, como salário médio e máximo, e a exibição de gráficos interativos.
Criação de Gráficos: Utilizamos o Plotly para criar gráficos que visualizam os dados de forma interativa, como gráficos de barras e histogramas.


https://share.streamlit.io/new
