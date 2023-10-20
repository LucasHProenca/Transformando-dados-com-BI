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

  - [x] Demonstrativos gráficos;
  - [x] Analise, transformação e interpretação da base de dados.  

---

## 📄 Análise e Transformação

Neste desáfio a ideia era a criação e hospedagem de um banco de dados que relacionava informações sobre os departamentos, suas localizações, funcionários e seus dependentes dentro da plataforma [Azure](https://azure.microsoft.com/pt-br/), e após isso realizar uma análise detalhada para as seguintes questões:

![questionario](https://github.com/LucasHProenca/Transformando-dados-com-BI/assets/106993403/b18eb764-81d5-43f3-9357-55c35245b5a0)

### ATENÇÃO!

#### A fim de não compromoter dados seguros, alguns dados foram modificados apenas para sanar essas questões.

![endereco](https://github.com/LucasHProenca/Transformando-dados-com-BI/assets/106993403/bc6af0d3-0461-46c5-b7ea-68d75be40cf4)


Anteriormente, a coluna "endereço" era algo complexo, e para melhorar sua visualização, resolvemos desfragmenta-la em "Número, Bairro, Cidade e Estado"

![mesclaEmpregadosEDpt](https://github.com/LucasHProenca/Transformando-dados-com-BI/assets/106993403/b0aeac00-31af-411a-a699-22a7bf8ea7c9)


Dentro da base dados recebida, tinhamos no inicio duas tabelas separadas "Departamentos" e "Empregados" então, decidimos mescla-las numa só para facilitar a compreensão dos dados, como mostra o exemplo acima.

Foi solicitado também a junção de dados entre "Gerentes" e "Gerenciados" com isso foi realizada a mescla entre a tabela "empregados" e "departamento dos empregados". Algo importante de se ressaltar, é que neste caso apesar de termos acesso ao identificador do gerente de cada funcionário inicialmente na tabela "empregados" não tinhamos acesso ao seu nome, então não seria possível atribuir os dados dentro da própria tabela, a unica forma encontrada foi realizando a mescla com outra tabela. 

![gerentesEEmpregados](https://github.com/LucasHProenca/Transformando-dados-com-BI/assets/106993403/bbb5fb64-995d-46c9-9df5-e0766b991ed1)


![graficoDeBarrasGEE](https://github.com/LucasHProenca/Transformando-dados-com-BI/assets/106993403/f6493d5b-ff56-4ccb-8a7e-d8cc3e8140f2)


E por fim era necessário realizar a conexão entre as tabelas "Departamentos" e "Localizações" afim de unir suas informações disponibilizando uma visualização simples, clara e objetiva dos dados.

![departamentosELocalizações](https://github.com/LucasHProenca/Transformando-dados-com-BI/assets/106993403/fb7061f2-b018-4172-8b27-424447bad797)


### Relatório 

Para demonstrar na prática do que essa base de dados se trata, criamos o seguinte demonstrativo. 

![relatorio](https://github.com/LucasHProenca/Transformando-dados-com-BI/assets/106993403/2b17c162-7fa3-4fc1-82b5-b509076aa9b5)


Como podemos ver nos dados do relatório acima, podemos ver quem são os gerentes, assim como quem são seus respectivos funcionários, a localização de cada departamento, com o salário de todos os funcionários pudemos comprovar que James Borg possui o maior cargo dentro da empresa, e próximo a ele Jennifer Wallace, Franklin Wrong e Ramesh Narayan ocupam as próximas posições, sendo os dois primeiros gerentes e o terceiro pudemos concluir que provavelmente será promovido em breve, considerando a proximidade salarial entre ele e os atuais gerentes.
Também podemos ver um mapa demonstrando o salário dos empregados de acordo com a cidade que trabalham e seu genero.

Podemos concluir então que a transformação dos dados foi bem sucedida e os gráficos trazem informações claras e objetivas, facilitando o entendimento do seu publico alvo.

---

## 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

-   **[Power BI](https://reactrouter.com/en/main)**
-   **[SQL](https://blog.betrybe.com/sql/)**

---

## 🦸 Autor

 <img style="border-radius: 50%;"  src="https://github.com/LucasHProenca/Labecommerce-back-end/assets/106993403/9abf8ee7-9527-42f8-9151-04ccd3db2d97" width="100px;" alt="" />
 <br />
 <sub><b>Lucas Henrique Proença</b></sub>
 <br />

[![Linkedin Badge](https://img.shields.io/badge/-Lucas-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/lucas-proen%C3%A7a-512650106/)](https://www.linkedin.com/in/lucas-proen%C3%A7a-512650106/) 

---

