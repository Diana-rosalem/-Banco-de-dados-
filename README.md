# -Banco-de-dados-
<h1>Trabalho de banco de dados UVV </h1>
<li> Grupo: Diana Rosalem, Aline Amy Kato, Bernardo Zampirole.</li>
<li>Professor: Marcello Novaes De Amorin </li>
<br> DESCRIÇÃO:
<br>
<br> Uma empresa é dona de um site de crítica sobre filmes recém lançados.
<br>
<br> Para realizar as críticas possui uma equipe de funcionários especializada, que cada integrante recebe uma parte do dinheiro arrecadado de acordo com a quantidade de matérias que fazem, além disso em toda avaliação eles convidam um crítico renomado, que possui algum certificado, para uma parte da matéria que também recebe uma comissão, diferente dos funcionários, por cada trabalho realizado.
<br>
<br> Na empresa existe uma equipe de manutenção e suporte do site que mensalmente realiza uma busca por erros e bugs do site. 
<br>
<br> Os usuários cadastrados também podem fazer uma avaliação sobre a o filme e dos integrantes da equipe de acordo com as matérias publicadas.
<br>
<br>A cada ano realizam uma classificação dos melhores filmes com base nas avaliações da equipe e dos usuários.
<br>
<br>
<h2> Normalização do banco de dados</h2>
<br>
  <br>Primeira forma normal: os atributos só podem ter um único valor, ou seja, não possuem repetições (não são atributos   multivalorados), caso houver é preciso separar e/ou criar outros atributos, para transforma-lo em um atributo de valor único se não resolver então deve criar uma entidade adicional para se relacionar com original.
<br>
  <br>Segunda forma normal: deve atender todos os requisitos da primeira forma, e serve para prevenir que o identificador único não depende totalmente, e torná-lo dependente, no caso de haver um UID composto ambos deverão ser dependentes. se não for dependente deve se criar uma outra entidade.
<br>
  <br>Terceira forma normal: os atributos só podem depender o UDI da entidade, se caso haver um atributo que depende de outro sem ser o UDI (dependências transitivas), deve se movê-lo para uma nova entidade.
