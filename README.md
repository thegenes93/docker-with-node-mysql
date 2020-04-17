# Docker with node mysql
________________________________________________________________________________________________________________________________

Projeto desenvolvido em meio a uma necessidade de reduzir a carga de trabalho para criar um ambiente para
desenvolvimento mais agil.

Nesse projeto foi ultilizado:
* Docker
* Docker-compose
* Node.js
* Mysql
* Express
* Nodemon

# Como usar
________________________________________________________________________________________________________________________________

* Instale o node
        https://nodejs.org/en/


* Instale o docker
        https://www.docker.com/products/docker-desktop

* instale as dependências
        Acesse a parta /node no terminal e execute
            npm install

Construindo imagens

* container Mysql
        Acesse a pasta db no terminal e execute
            docker build -t mysql -f .

* container Node
        Acesse a pasta node no terminal e execute
            docker build -t node -f .

Execultando os Containers

 * container Mysql
        No terminal execute
          docker run -d --rm --name mysql-container mysql

 * container Node
        No terminal execute
            docker run -d --rm --name node-container node


Execultando o docker-compose
        No terminal execulte
            docker-compose up

________________________________________________________________________________________________________________________________

Para testar o node acesse o link http://localhost:3000

Para testar o mysql abra o workbench{
    hostname: localhost
    port:3306
    user: root
    password:123
}

obs: Caso ocorra algum problema ao execultar o docker-compose up, para ou remova os conteiner ativos.


