# PROJETO-COVID-19-2021
Desenvolvemos um dashboard interativo para visualização e exploração dos dados da evolução da pandemia de COVID-19 e da vacinação no Brasil. Utilizamos o Google Data Studio para o dashboard, e as fontes de dados foram os casos da Universidade John Hopkins e os dados de vacinação da Universidade de Oxford.

1. Introdução

1.1. Resumo Rápido (TLDR)
Desenvolvemos um dashboard interativo para visualização e exploração dos dados da evolução da pandemia de COVID-19 e da vacinação no Brasil. Utilizamos o Google Data Studio para o dashboard, e as fontes de dados foram os casos da Universidade John Hopkins e os dados de vacinação da Universidade de Oxford.

1.2. Pandemia Coronavírus 2019
A COVID-19 é uma infecção respiratória aguda causada pelo coronavírus SARS-CoV-2, potencialmente grave, de elevada transmissibilidade e de distribuição global (Fonte: Governo Brasileiro).

1.3. Dados
Os dados sobre casos da COVID-19 são compilados pelo Centro de Ciência de Sistemas e Engenharia da Universidade John Hopkins. Os dados são atualizados diariamente desde janeiro de 2020, com granularidade temporal diária e geográfica por regiões de países (estados, condados, etc.). Os dados de vacinação da COVID-19 são compilados pelo projeto "Nosso Mundo em Dados" (Our World in Data - OWID) da Universidade de Oxford. Os dados também são atualizados diariamente desde janeiro de 2020, com granularidade temporal diária e geográfica por países.

2. Análise Exploratória de Dados
Nesta sessão vamos utilizar os seguintes pacotes Python para processar os dados bruto em um formato adequado para um painel para exploração interativa de dados.

2.1.1. Extração
O dado está compilado em um arquivo por dia, exemplo para 2021/12/01.

2.1.2. Wrangling
Vamos manipular os dados para o dashboard. O foco é em garantir uma boa granularidade e qualidade da base de dados.

2.1.3. Carregamento
Com os dados manipulados, vamos persisti-lo em disco, fazer o seu download e carrega-lo no Google Data Studio.
