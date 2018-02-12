# Node.js com Balancer

Projeto executado como aprendizado no curso de Docker da Alura.
Desenvolvido projeto com 3 **Nodes** distribuido pelo balanceador **NGINX** e consultando o mesmo banco de dados em **MongoDB**. 

# Docker Compose

Docker Compose buildado o **NGINX** em um container e exibindo-o na porta 80:80, também são gerados outros 3 containers com os **Node.js** que consulta e publica conteudo ao banco de dados que está em outro container com a imagem do **MongoDB**.

#### Start
Iniciando com o **DOCKER-COMPOSE**
```sh
$ docker-compose build
$ docker-compose up -d
```