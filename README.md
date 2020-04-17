# Docker with node mysql
________________________________________________________________________________________________________________________________________________________________

Project developed amid a need to reduce the workload to create an environment for
more agile development.

In this project it was used:
* Docker
* Docker-compose
* Node.js
* Mysql
* Express
* Nodemon

# How to use
________________________________________________________________________________________________________________________________________________________________

* Install the node
https://nodejs.org/en/


* Install the docker
https://www.docker.com/products/docker-desktop

* install the dependencies
Access the part / node in the terminal and execute
npm install

Building images

* Mysql container
Access the db folder in the terminal and run
docker build -t mysql -f.

* Node container
Access the node folder in the terminal and run
docker build -t node -f.

Running the Containers

* Mysql container
At the terminal run
docker run -d --rm --name mysql-container mysql

* Node container
At the terminal run
docker run -d --rm --name node-container node


Running the docker-compose
At the terminal run
docker-compose up

________________________________________________________________________________________________________________________________________________________________

To test the node, access the link http: // localhost: 3000

To test mysql open the workbench {
hostname: localhost
port: 3306
user: root
password: 123
}

note: If there is  problem when running the docker-compose up.
Stop or remove the active containers.



________________________________________________________________________________________________________________________________
________________________________________________________________________________________________________________________________
________________________________________________________________________________________________________________________________




        

# Docker com node mysql
________________________________________________________________________________________________________________________________

Projeto desenvolvido em meio a uma necessidade de reduzir a carga de trabalho para criar um ambiente de desenvolvimento mais ágil.

Nesse projeto foi utilizado:
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
        Acesse a pasta node / no terminal e execute
            npm install

Construindo imagens

* container Mysql
        Acesse a pasta db no terminal e execute
            docker build -t mysql -f .

* container Node
        Acesse a pasta node no terminal e execute
            docker build -t node -f .

Executando os Containers

 * container Mysql
        No terminal execute
          docker run -d --rm --name mysql-container mysql

 * container Node
        No terminal execute
            docker run -d --rm --name node-container node


Executando o docker-compose
        No terminal execute
            docker-compose up

________________________________________________________________________________________________________________________________

Para testar o node acesse o link http://localhost:3000

Para testar o mysql abra o workbench{
    hostname: localhost
    port:3306
    user: root
    password:123
}

obs: Caso ocorra algum problema ao executar o docker-compose up, para ou remova os conteiner ativos.
