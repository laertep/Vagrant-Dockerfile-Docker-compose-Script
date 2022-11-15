### Projeto - Vagrant/Dockerfile/Docker-compose/Script

$ Instalação do VirtualBox/Vagrant na maquina Host;
* Sincronização da pasta host - /nginx-desafio05 para pasta /home/vagrant guest;

$ Instalação do Docker/Dockerfile através do Shell - inline
* Atualização da VM - update;
* Instalação do serviço docker;
* Configuração e personalização do arquivo dockerfile na pasta nginx-desafio05 - imagem Nginx na porta 80;
* Criação do docker através do comando docker run com a imagem criada do dockerfile.

$ Configuração do docker-compose.sh via Shell script - inline;
* Criação do arquivo docker-compose.yml na pasta nginx-desafio05 para rodar aplicação Nginx na porta 8080;
* Parametrizando os arquivos index.html e nginx.conf através da configuração dos volumes;
* Execução do docker compose - docker-compose up -d 

![image](https://user-images.githubusercontent.com/44216245/201802176-41b75538-5075-46b4-8a3c-a879e91bb3f8.png)
