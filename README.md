# R para Data Science: Aplicando Data Visualization com ggplot2

Boas-vindas a mais um curso de **R para Data Science** da Alura!

Esse Github foi produzido com muito carinho para você montar o seu portfólio com as atividades do curso e elaborar suas próprias hipóteses, testar as técnicas exploradas dentro do curso e também adicionar outras durante a prática conciliando a linguagem R e os pacotes do tidyverse. Tudo isso voltado ao tema de visualização de dados.

O objetivo deste curso é aprender a construir diferentes tipos de visualização de dados utilizando a linguagem R. Por meio do ggplot2 e de outros pacotes do tidyverse, você conseguirá escolher qual tipo de visual é o mais adequado para representar as análises de acordo com as perguntas e demandas requisitadas para o problema. Durante o curso, vamos diferenciar a análise exploratória (analisar e criar hipótese) da explanatória (comunicar e persuadir), gerar e personalizar gráficos e adicionar outros recursos visuais como anotações, rótulos e legenda de dados. Ao final do curso, você será capaz de gerar visualizações personalizadas, fáceis de ler e voltadas ao tipo de público que você deseja.

É importante que você tenha conhecimento da **linguagem R**, bem como o básico de alguns pacotes do **tidyverse** como **dplyr**, **ggplot2**, **readr** e **lubridate**.

## Introdução

![](imagens/logos/logo_branca_fundo_azul.png){alt="inserir alt"}

Neste curso, vamos trabalhar com o storytelling da empresa fictícia **Zoop**, uma grande varejista que atende a todas as regiões do Brasil por meio do seu **e-commerce**. Ela é conhecida pela ampla variedade em seus produtos buscando atender a todo tipo de público.

Para gerenciar o seu alcance, bem como o faturamento de seu setor em lojas online, ela consolida os dados em diferentes períodos de tempo e avalia esses dados para gerar insights e tomar algumas decisões estratégicas em seu negócio. Neste projeto, vamos ter acesso aos dados de parte da sua clientela do e-commerce dentro do ano de 2023.

Você, como **cientista de dados júnior** da empresa, precisará gerar visuais que auxiliem na construção de relatórios de acordo com algumas premissas passadas pelas partes interessadas realizando uma rápida análise do público que possuimos na loja virtual e do faturamento da empresa.

### **Problema de negócio:**

O time de dados da **Zoop** precisa extrair os dados e gerar informações por meio de visuais que possam ser apresentados a diretoria da empresa apontando os dados de faturamento, perfil do cliente e outros indicadores que possam auxiliar na tomada de decisão em sua loja online.

### **Base de dados**

Vamos importar duas bases de dados:

> Dados de clientes do e-commerce da Zoop, separados pelo código identificador da compra.

> Dados de vendas do e-commerce da Zoop em 2023, separados pelo código identificador da compra.

Esses dados serão lidos a partir do repositório compartilhado pelo GitHub.

### **Desafio**

Você, como um(a) cientista de dados júnior, passará por um treinamento a fim de testar seus conhecimentos de análise de dados para entrar no time de dados da Zoop. O seu desafio é **extrair os dados** da base de clientes e vendas da empresa e **construir visuais** que possam agregar valor à apresentação dos resultados da Zoop em 2023. Para isso, serão repassados algunsquestionamentos que foram separados para que você possa contribuir na construção do storytelling das vendas da empresa.

Como grande parte dos analistas do time de dados utilizam a **linguagem R**, você precisará realizar o processo da análise exploratória dos dados (AED) e a criação dos visuais utilizando essa linguagem.

## Paleta de Cores

Neste projeto, utilizaremos a paleta de cores abaixo, passada por meio de uma entrevista com o time de UX/UI da Zoop.

| red_1                               | red_2                               | red_3                               | grey_1                               | grey_2                               | grey_3                               | blue_1                               | blue_2                               | blue_3                               |
|--------|--------|--------|--------|--------|--------|--------|--------|--------|
| #ee8399                             | #e23155                             | #881d33                             | #f3f3f3                              | #ebebeb                              | #8d8d8d                              | #a3adbd                              | #5e708c                              | #19325b                              |
| ![](imagens/paleta_cores/RED_1.png) | ![](imagens/paleta_cores/RED_2.png) | ![](imagens/paleta_cores/RED_3.png) | ![](imagens/paleta_cores/GREY_1.png) | ![](imagens/paleta_cores/GREY_2.png) | ![](imagens/paleta_cores/GREY_3.png) | ![](imagens/paleta_cores/BLUE_1.png) | ![](imagens/paleta_cores/BLUE_2.png) | ![](imagens/paleta_cores/BLUE_3.png) |

Como sugestão para outros projetos que você desenvolver, existem sites como o [Coolor](https://coolors.co/palettes/trending) ou [imagecolorpicker](https://imagecolorpicker.com/) que fornecem ideias de paletas e cores que ornam bem se relacionadas.

## Visualizações que exploraremos

Vamos explorar **3 subgrupos** de visualização de dados, sendo eles:

-   Comparação
-   Distribuição
-   Composição

Para este curso, focamos nos seguintes visuais:

-   Gráfico de Colunas
-   Gráfico de Barras
-   Gráfico de Linha
-   Gráficos de Colunas Agrupadas e Empilhadas
-   Histograma
-   Boxplot

## Conclusões

Esse curso teve como objetivo aprender a trabalhar na análise e geração de visualização de dados com a Linguagem R visando o desenvolvimento de um storytelling sobre as vendas e perfil dos clientes de uma empresa fictícia.

Exploramos os processos de extração, tratamento e visualização de dados, criação de scripts em R e construção de visuais exploratórios (voltados a investigação e geração de insights) e explanatórios (voltados a aprensentação ao público e às partes interessadas).

Criamos gráficos dos mais diversos tipos partindo do uso das bibliotecas mais utilizadas em R, personalizando-os e adicionando recursos visuais como anotações, destaques, legenda de dados e outras técnicas de visualização.

Ao concluir este curso, você será capaz de gerar um documento **Quarto** com todo esse processo voltado a um storytelling com dados, praticando diversos conceitos utilizados no dia a dia das empresas.

Sinta-se à vontade para fazer o fork desse projeto e construir o seu portfólio! 😊
