## <h1 align="center"> Descrição do Projeto Biblioteca :books: </h1>
<h4 align="center"> 
    :construction:  Projeto em construção  :construction:
</h4>
O presente projeto nasceu de uma atividade da Alura (escola de cursos online em tecnologia) para a formação em Dados, <b>7 Days of code</b> e foi desenvolvido 100% em Python. Os dados foram extraídos dessa atividade e a estes dados foram adicionados um plano de negócio detalhado, análises com teste de hipótese e outras abordagens gráficas para visualizar a variação do número de empréstimos, todos estes acréscimos são 100% autorais. 

O objetivo do trabalho foi fornecer a nova gestão da Biblioteca Central UFRN, uma visão completa do funcionamento da instituição a partir dos dados. Como esta será a primeira gestão a realizar todas as tomadas de decisões com base em dados, foram entregues os resultados do número de empréstimos geral da biblioteca; quais acervos são os mais acessados, quais cursos mais utilizaram o serviço de empréstimos da biblioteca e foram verificados os horários e meses de maior e menor movimento da biblioteca para organização interna dos funcionários, com foco na realização de atividades de capacitação, folgas e férias.

## <h1 align="center"> Métodos e Bibliotecas 🖥️: </h1> 

### Principais métodos para o Tratamento dos Dados: 💾:
* Utilização dos métodos `.read_csv()`, `.read_json()`, `.head()`, `.rename()`, `.concat()`, `.to_datetime()`, `.merge()`, `.sort_values()`, `.pivot_table()`, `.drop()`, `.reset_index()` da biblioteca Pandas;

### Bibliotecas PYTHON para realização da EDA e dos Testes: :panda_face: 
* PANDAS
* NUMPY
* SEABORN
* MATPLOTLIB
* SCIPY.STATS

## <h1 align="center"> Principais Lições :relaxed: </h1> 
O desenvolvimento desse projeto foi muito desafiador, pois as variáveis de número de empréstimos não estavam disponíveis nos dados baixados, sendo a única informação disponível com relação aos empréstimos era a data e o número de matricula realizado por cada aluno. A data de empréstimo estava associada a outras informações que puderam ser associadas posteriormente com as funções de agrupamento. No entanto, para fornecer os números de empréstimos por ano, meses, horas, usuários, etc, foi necessário realizar diversos tratamentos para extraí-los. 

A principal abordagem foi transformar as datas de empréstimos que estavam tipo  em datetime e aplicar funções de agrupamento para construir a informação do número de empréstimos. A partir daí, pode-se realizar a EDA, gerando conclusões e insights para a equipe gestora.

Assim, na construção desse projeto pude explorar e desenvolver os atributos de extração, manipulação e tratamento dos dados, muito utilizados na análise de dados, bem como utilizar a parte gráfica para explicitar o que os números estavam mostrando, onde prosseguir e desenvolver testes de hipóteses para pode realizar afirmações a respeito da tendência geral. A soma dessas etapas todas, resultou em insights que nortearão as decisões futuras da equipe gestora.

#### Agradecimento Especial ao Francisco Tadeu Foz:raised_hands: 
Muito obrigado pelas trocas em todo o processo de desenvolvimento deste projeto!!

#### Disclaimer: **Neste projeto, a formatação foi modificada em relação ao que foi proposto na atividade, a fim de caracterizar um plano de negócio, onde todas as interpretações das análises e insights propostos são originais do autor.**
