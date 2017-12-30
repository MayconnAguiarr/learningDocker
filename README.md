# learningDocker

    DOCKERFILE - É um documento de texto que contém todos os comandos que um usuário utiliza
    em um terminal para montar uma imagem.

    DOCKER-COMPOSER - É uma ferramenta para a criação e execução de múltiplos containers de aplicação.
    Com o Compose, você usar um arquivo do tipo yaml para definir como será o ambiente de sua aplicação e
    usando um único comando você criará e iniciará todos os serviços definidos.

## Objetivo
    Criar containers configurados usando DockerFile e DockerComposer.

## Instalação Docker (Linux)    
    1. sudo apt-get update
    2. sudo apt-get -y install docker.io 
    3. sudo ln -sf /usr/bin/docker.io /usr/local/bin/docker
        
## Como testar DcokerFile ?
    1. Clone o repositório
    2. Acesse a pasta clonada e logo em seguida a pasta DockerFile
    3. docker build -t ubuntu/apache2 .
    4. docker run -d -p 8080:80 ubuntu/apache2
    5. http://172.17.0.2/docker.html (Verificar IP)

## Como testar Docker-Composer ?


   
## Alguns comandos
    docker ps - Lista os containers em execução.
    docker inspect nomeContainer - Mostra toda configuração de rede.
    
