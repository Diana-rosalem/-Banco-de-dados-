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
  <br>Primeira forma normal: Os atributos só podem ter um único valor, ou seja, não possuem repetições (não são atributos multivalorados), caso houver é preciso separar e criar outros atributos, para transforma-lo em um atributo de valor único. Se não resolver então deve criar uma entidade adicional para se relacionar com original.
<br>
  <br>Segunda forma normal: Deve atender todos os requisitos da primeira forma, e serve para prevenir ter outros atributos que não depende totalmente do UID, e torná-los dependente, no caso de haver um UID composto ambos deverão ser dependentes. Se não for dependente deve se criar uma outra entidade.
<br>
  <br>Terceira forma normal: Deve atender todos os requisitos da primeira e segunda forma. Os atributos só podem depender o UID da entidade, ou seja, não devem depender um do outro (sem ser o UID), se caso haver um atributo que depende de outro sem ser o UDI (dependências transitivas), deve se movê-lo para uma nova entidade ou removê-lo.
 <br>
 <br>
 <h2>Perguntas do sistema</h2>
<br>-Quais filmes foram avaliados?  (Relacionamento da matéria com o filme atributo nome)
<br>- Quais as matérias feitas?  (entidade matéria)
<br>- Quem fez a matéria?  (entidade crítico relacionamento com a matéria)
<br>- Quantas matérias foram feitas por determinado crítico?  (crítico relacionamento com a matéria) 
<br>- Quais são os usuários cadastrados?  (entidade usuário, atributo e-mail)
<br>- Quem é o crítico renomado de cada matéria? (entidade filho: crítico-renomado com relacionamento na matéria)
<br>- Quem é funcionário da empresa?  (atributo matrícula)
<br>- Quais são as classificações dos melhores filmes de cada ano?  (entidade avaliação e filmes)
<br>- Quais são as avaliações dos usuários?  (relacionamento da avaliação e usuário)
<br>- Quais são as avaliações de cada filme?  (relacionamento entre avaliação)

  
