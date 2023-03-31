
# Manual de Instalação

### Pré-Requesitos para a instalação:
- Docker; <br>
- Node JS; <br>
- Java 17 ou superior;<br>
- Recomendamos Eclipse ou IntelliJ como IDE para o JAVA (back-end).
- Recomendamos o VSCode como IDE para o React (front-end).

        
### Etapa 1:
- Clonando o Repositório:
- Execute o comando:
```
git clone --recurse-submodules https://github.com/whatscodeg3/API-3DSM.git
```
- Após isso acesse a pasta utilizando:
```
cd API-3DSM
```
- Execute o comando para atualizar os submodules:
```
git submodule update --recursive --remote
```

### Etapa 2:
- Utilizando o DOCKER:
- Execute o comando estando na raiz do projeto:
```
docker-compose up -d --build --force-recreate
```


### Etapa 3:
- Rodando os Servidos do JAVA (Back-end).
- Inicialize seu MAVEN com o Clean Install, assim, todas as dependência necessárias serão baixadas.
- Dentro da pasta "java" acesse a classe APPLICATION e execute-a.


### Etapa 4:
- Rodando o serviço do Front-End
- Em sua IDE execute o terminal utilize o seguinte comando dentro da pasta principal do projeto:
```
npm install
```
- Acesse a pasta src com seguinte comando:
```
cd src
```



