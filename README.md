# Project-facu001

Comandos sera usado para o uso do docker
<h3> --Build </h3>
docker-compose build: Constrói (ou reconstrói) as imagens dos serviços definidos no arquivo docker-compose.yml. </br>
<h3> --Iniciando </h3>
docker-compose up: Inicia os contêineres conforme definido no arquivo docker-compose.yml. </br>
docker-compose up -d: Inicia os contêineres em segundo plano (detached mode). </br>
ou  </br>
docker-compose start: Inicia os contêineres para os serviços definidos no arquivo docker-compose.yml. </br>
<h3>--Parando os contêineres </h3> 
 </br>
docker-compose stop: Para os contêineres para os serviços definidos no arquivo docker-compose.yml, mantendo os recursos  associados. </br>
ou </br>
docker-compose down: Para e remove os contêineres, redes e volumes definidos no arquivo docker-compose.yml. </br>
<h3>--Listando os contêineres </h3>
docker-compose ps: Lista os contêineres em execução para os serviços definidos no arquivo docker-compose.yml. </br>
<h3>--Reiniciando</h3>
docker-compose restart: Para e reinicia os contêineres para os serviços definidos no arquivo docker-compose.yml. </br>
--Executando algum comando dentro do docker </br>
docker-compose exec mysql mysql -u alunos -p (acessando o banco de dados no docker) </br>
<h3>-- Exibição de logs</h3>
docker-compose logs: Exibe logs de saída dos contêineres para todos os serviços definidos no arquivo docker-compose.yml. </br>
