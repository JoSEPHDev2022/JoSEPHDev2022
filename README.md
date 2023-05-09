![banner](https://raw.githubusercontent.com/JoSEPHDev2022/JoSEPHDev2022/main/bann.png)

---
<h1>
    <p align="center">
        <b>Portfólio 📋</b>
    </p>
</h1>

A seguir, os projetos centrais de destaque no meu perfil!

<h3>
<p align="center">
    <b>
    1. Processo de ETL: Carregamento, Transformação e Análise de Dados Financeiros pelo Power BI
    </b>
</p>
</h3>

Link > https://github.com/JoSEPHDev2022/Dash_Financeiro_Power_BI

>O objetivo central desse projeto foi de desenvolver minhas capacidades de extração de dados, transformação desses registros utilizando a linguagem DAX do Power BI, engenharia de atributos e criação de medidas na plataforma de dashboards, assim como também criar um dashboard com um design intuitivo e amigável, com cores e padronizações especificas para cada empresa e seu respectivo relatório.

<h3>
<p align="center">
    <b>
    2. Análise Exploratória Descritiva-Estatistica de Dados: Site de Filmes Pirateados
    </b>
</p>
</h3>

Link > https://github.com/JoSEPHDev2022/EDA_Pirated_Movies

> Este projeto tem como objetivo servir de aprimoramento em minhas capacidades de análise de dados utilizando estatística descritiva, gráficos e plots com Python,
manipulação de dados com Pandas entre outras coisas. Como toda Análise Exploratória que realizo, esse projeto segue um caminho definido de etapas (esse caminho está descrito mais abaixo neste README). Por se tratar de um projeto bem detalhado e com várias etapas, ele ainda encontra-se em produção, porém deixo em destaque por se tratar do meu projeto mais recente e avançado de EDA.

<h3>
<p align="center">
    <b>
    3. Machine-Learning com Power BI: Utilizando o Power BI em Conjunto com Python Para Criar Visualizações
    </b>
</p>
</h3>

Link > https://github.com/JoSEPHDev2022/Dash_Machine_Learning/tree/master

> Nesse projeto, utilizei de técnicas de Machine Learning para realizar a Clusterização de Clientes de um dataset fictício. Após isso, foi criado um Dashboard pelo próprio Jupyter, Dash que foi publicado para o Power BI Service para poder ser aberto no Power BI Desktop para manipulação final.

<h1>
    <p align="center">
        <b>Mas afinal, quem sou eu? 📰 </b>
    </p>
</h1>


Olá! me chamo José Luiz, um brasileiro residente do estado de São Paulo que está em busca de um constante aprimoramento profissional na área de Dados! Para uma visão mais holistica sobre mim, recomendo uma passadinha em meu [LinkedIn](https://www.linkedin.com/in/jose-luiz-ferreira-junior/)! Mas para dar alguns bullet-points:

- 👨‍💻 Atualmente estou focando em aprimorar minhas habilidades com Python, focando em me especializar ainda mais em Data Analytics, principalmente com Análise Exploratória de Dados usando estatística;

- 🔭 Atualmente trabalho como professor assistente na mesma instituição em que estudei análise de dados! Resília Educação. Lá eu ensino e ajudo os alunos a aprender e crescer usando a linguagem Python para fazer projetos incríveis de análise de dados;

- Gosto de jogar games, codar, fazer projetos paralelos como análise exploratória de dados em vários conjuntos de dados, ouvir música metal (banda favorita: Bolt Thrower 🎧 🤘) e dar muito carinho nas minhas gatinhas ❤️🐱;

- 💬 Adoro conversar com as pessoas e compartilhar histórias.

- ⚡ Curiosidade: sou formado em História e desenvolvi um projeto de pesquisa acadêmica na área, antes de vir para a área de Data Analysis!

Por aqui você encontrará uma gama de repositórios, alguns pertencentes ao meu período de estudante na Resilia Educação, onde esses projetos geralmente consistem em programação em Python e conceitos mais simples, contendo código escrito por um iniciante em Python! Por mais que esses projetos estejam desatualizados e eu já tenha ultrapassado as habilidades apresentadas neles, sempre acho legal deixá-los amostra para demonstrar minha evolução na área!

Os projetos centrais são de Análise Exploratória de Dados, algo que amo fazer em todo tipo de Dataset. Cheque a seção de "Portfólio" para entrar em contato com os mais recentes e avançados.

<h1>
    <p align="center">
        <b>Tecnologias que Utilizo Diariamente 💻 </b>
    </p>
</h1>

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)  ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) | Seaborn |![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black) | Tableau |

<h1>
    <p align="center">
        <b>Etapas do Processo de Criação de uma EDA: Um Guia Detalhado 📊 </b>
    </p>
</h1>

**1. Compreendendo os Dados**

Nesta primeira etapa, após coletar e importar os dados, trabalho para obter uma ideia geral do Dataset e, para isso, utilizo os seguintes métodos do Pandas:

```python
data.describe()    # Descrição estatística das variáveis.
data.info()        # Informações gerais sobre as variáveis, como dtypes e uso de memória.
data.isna()        # Contagem do total de pontos de dados nulos.
data.shape()       # As dimensões do conjunto de dados (quantas linhas e colunas).
```

**2. Preparando e Transformando os Dados**

Esta etapa é muito importante, pois é onde manipulo o conjunto de dados, alterando tipos de dados, nomes de variáveis ​​e também projetando novos recursos para o conjunto de dados, ou seja, crio novas variáveis ​​com base nas existentes para aumentar ainda mais minhas capacidades de análise. Em outras palavras, essa etapa consiste em:

- Eliminar variáveis ​​inúteis ou indesejáveis;

- Renomear as variáveis, se necessário;

- Lidar com valores ausentes;

- Alterar tipos de dados;

- Lidar com duplicatas;

- Adicionar novos recursos ao conjunto de dados (engenharia de recursos).

**3. Análise Univariada**

Aqui começo minha avaliação em busca de outliers e, para isso, uso principalmente os seguintes recursos:

```python
data.hist()            # Histograma para visualizar a distribuição dos dados.
data.value_counts()    # Determine quais pontos de dados estão ocorrendo mais vezes na variável.
data.skew()            # Determine a assimetria dos dados.
data.kurt()            # Determine a Curtose dos dados.
``` 

Para referência, é assim que determinamos assimetria:

![skew_graph](https://www.biologyforlife.com/uploads/2/2/3/9/22392738/c101b0da6ea1a0dab31f80d9963b0368_orig.png)

E, para a Curtose:

![kurt_graph](https://ars.els-cdn.com/content/image/3-s2.0-B9780128168189000159-f05-02-9780128168189.jpg)

**4. Análise multivariada**

É aqui que analiso a correlação entre as diferentes variáveis ​​do Dataset, para isso, utilizo os heatmaps, pairplots e boxplots da biblioteca seaborn.


**5. Perguntas, percepções e respostas**

Como etapa final, faço várias perguntas relevantes após a análise dos dados, buscando descobrir os insights mais relevantes para aquele conjunto de dados específico.

<h1>
    <p align="center">
        <b>Contatos 📫 </b>
    </p>
</h1>

Gostou do que viu por aqui? Tem feedbakcs para me dar? Quer bater um papo sobre meus projetos e ideias? Entre em contato por:

[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jose-luiz-ferreira-junior/)

![Outlook](https://img.shields.io/badge/Microsoft_Outlook-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white)

jl_ferreira16@hotmail.com