<div align="center">
<img src="https://github.com/LucasHProenca/Power-BI-Analyst/assets/106993403/c05ab973-8cc0-4555-949c-7a6329eef069" alt="" />
</div>


---

<p align="center">
 <a href="#-sobre-o-projeto">Sobre</a> •
 <a href="#-funcionalidades">Funcionalidades</a> •
 <a href="#-análise-e-transformação">Análise e Transformação</a> • 
 <a href="#-tecnologias">Tecnologias</a> • 
 <a href="#-autor">Autor</a> • 
</p>

## 💻 Sobre o projeto 

 
📟 Análise e Transformação de Dados - Esse projeto teve como objetivo interpretar e transformar uma base de dados para a obtenção de informações pertinentes para a geração de um relatório simples de uma empresa.

Projeto desenvolvido durante o **Bootcamp de Ciência de Dados com Python** da [DIO](https://www.dio.me/en).
Esse bootcamp é uma experiência online, um programa com mais de 80 horas de experiência prática nas principais tecnologias que norteiam o Python, também oferece desafios de código e projetos individuais.

---

## ⚙️ Funcionalidades

  - [x] Diversos demonstrativos gráficos;  

---

## 📄 Análise e Transformação

Neste desáfio a ideia era a criação e hospedagem de um banco de dados que relacionava informações sobre os departamentos, suas localizações, funcionários e seus dependentes dentro da plataforma [Azure](https://azure.microsoft.com/pt-br/), e após isso realizar uma análise detalhada para as seguintes questões:

![questionario](https://github.com/LucasHProenca/Transformando-dados-com-BI/assets/106993403/b18eb764-81d5-43f3-9357-55c35245b5a0)

### ATENÇÃO!

#### A fim de não compromoter dados seguros, alguns dados foram modificados apenas para sanar essas questões.

![endereco](https://github.com/LucasHProenca/Transformando-dados-com-BI/assets/106993403/bc6af0d3-0461-46c5-b7ea-68d75be40cf4)


Anteriormente, a coluna "endereço" era algo complexo, e para melhorar sua visualização, resolvemos desfragmenta-la em "Número, Bairro, Cidade e Estado"

![mesclaEmpregadosEDpt](https://github.com/LucasHProenca/Transformando-dados-com-BI/assets/106993403/b0aeac00-31af-411a-a699-22a7bf8ea7c9)


Dentro da base dados recebida, tinhamos no inicio duas tabelas separadas "departamentos, empregados" então, decidimos mescla-las numa só para facilitar a compreensão dos dados, como mostra o exemplo acima.

Foi solicitado também a junção de dados entre "Gerentes" e "Gerenciados" com isso foi realizada a mescla entre a tabela "empregados" e "departamento dos empregados". Algo importante de se ressaltar, é que neste caso apesar de termos acesso ao identificador do gerente de cada funcionário inicialmente na tabela "empregados" não tinhamos acesso ao seu nome, então não seria possível atribuir os dados dentro da própria tabela, a unica forma encontrada foi realizando a mescla com outra tabela. 

![gerentesEEmpregados](https://github.com/LucasHProenca/Transformando-dados-com-BI/assets/106993403/bbb5fb64-995d-46c9-9df5-e0766b991ed1)


E por fim era necessário realizar a conexão entre as tabelas "Departamentos" e "Localizações" afim de unir suas informações disponibilizando uma visualização simples, clara e objetiva dos dados.

![departamentosELocalizações](https://github.com/LucasHProenca/Transformando-dados-com-BI/assets/106993403/fb7061f2-b018-4172-8b27-424447bad797)


### Desktop 

#### Página 1 - Relatório de Vendas 

![VendasP1](https://github.com/LucasHProenca/Power-BI-Analyst/assets/106993403/b2d7f23b-3300-4795-9031-a3d12d076312)

A página inicial do relatório pode ser vista de duas formas diferentes: Na primeira, como podemos observar pela foto acima, os gráficos de Vendas X Segmento e Total de Vendas X País são respectivamente, um gráfico de barras e um mapa, no entanto os botões presentes próximos aos mesmos nos possibilitam a alteração para um gráfico no formato de Donut, no caso de Vendas X Segmento, e um Tree Map, no caso de Total de Vendas X País, como podemos observar na imagem abaixo:

![VendasP@](https://github.com/LucasHProenca/Power-BI-Analyst/assets/106993403/06152f5b-21b6-4c32-8ad1-0ace28e7ab41)


Lembrando que, é possível utilizar diversas ferramentas disponíveis neste relatório para uma visualização mais aprofundada, como por exemplo:

![VendasP3](https://github.com/LucasHProenca/Power-BI-Analyst/assets/106993403/50eafb8c-8bcb-4bb1-9873-5fca36bf00e2)


Caso queira alterar o período de análise, basta alterar no segmentador localizado no canto superior direito, como podemos ver na foto acima, agora o intervalo de análise é de exatamente 1 ano, entre 01/12/2013 e 01/12/2014.

![VendasP4](https://github.com/LucasHProenca/Power-BI-Analyst/assets/106993403/6da822e1-401b-42f5-828a-688d0b2799fa)


Também é possível selecionar apenas um mês ou um produto para a análise, no exemplo acima, foi selecionado o mês de outubro e automaticamente todos os gráficos se alteraram para trazer apenas estes dados.

Caso queira voltar aos dados iniciais do relatório, basta clicar no icone de borracha localizado no canto superior direito.

Para acessar a segunda página, basta clicar na seta localizada no canto inferior esquerdo.

#### Página 2 - Relatório de Lucros Detalhado

![LucroP1](https://github.com/LucasHProenca/Power-BI-Analyst/assets/106993403/df118801-780e-4057-bafa-5edbd110f469)


Já nesta página, podemos observar um detalhamento focado nos lucros, tanto por produto, quanto por ano, país, segmento e até mesmo por trimestre. Na tela inicial temos informações gerais sobre os lucros, mas para uma análise mais detalhada, também é possível utilizar o segmentador para visualizar apenas um ano desejado por exemplo, enquanto na primeira visualização estavamos dando foco para o ano de 2014, nesta, daremos foco ao ano de 2013.

![LucroP2](https://github.com/LucasHProenca/Power-BI-Analyst/assets/106993403/de5cc14b-fb0e-4009-9017-013f953142d3)


---

## 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

-   **[Power BI](https://reactrouter.com/en/main)**

---

## 🦸 Autor

 <img style="border-radius: 50%;"  src="https://github.com/LucasHProenca/Labecommerce-back-end/assets/106993403/9abf8ee7-9527-42f8-9151-04ccd3db2d97" width="100px;" alt="" />
 <br />
 <sub><b>Lucas Henrique Proença</b></sub>
 <br />

[![Linkedin Badge](https://img.shields.io/badge/-Lucas-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/lucas-proen%C3%A7a-512650106/)](https://www.linkedin.com/in/lucas-proen%C3%A7a-512650106/) 

---

