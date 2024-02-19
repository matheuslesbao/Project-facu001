# Project-facu001

Comandos sera usado para o uso do docker
--Build
docker-compose build: Constrói (ou reconstrói) as imagens dos serviços definidos no arquivo docker-compose.yml.
--Iniciando
docker-compose up: Inicia os contêineres conforme definido no arquivo docker-compose.yml.
docker-compose up -d: Inicia os contêineres em segundo plano (detached mode).
ou 
docker-compose start: Inicia os contêineres para os serviços definidos no arquivo docker-compose.yml.

--Parando os contêineres
docker-compose stop: Para os contêineres para os serviços definidos no arquivo docker-compose.yml, mantendo os recursos associados.
ou
docker-compose down: Para e remove os contêineres, redes e volumes definidos no arquivo docker-compose.yml.
--Listando os contêineres
docker-compose ps: Lista os contêineres em execução para os serviços definidos no arquivo docker-compose.yml.
--Reiniciando
docker-compose restart: Para e reinicia os contêineres para os serviços definidos no arquivo docker-compose.yml.
--Executando algum comando dentro do docker
docker-compose exec mysql mysql -u alunos -p (acessando o banco de dados no docker)
-- Exibição de logs
docker-compose logs: Exibe logs de saída dos contêineres para todos os serviços definidos no arquivo docker-compose.yml.
