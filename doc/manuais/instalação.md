
# Manual de Instalação

### Pré-Requesitos para a instalação:
- Docker; <br>
- Node JS; <br>
- Java 17 ou superior;<br>
- Microsoft Workbench; <br>
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
- Cadastrando o primeiro Administrador no banco de dados:
- Acesse seu Microsoft Workbench e entre na primeira instância gerada pelo docker, como padrão com o nome 'Local Instance':
- Utilize o seguinte código para cadastrar um Administrador inicial:
```
INSERT INTO `payment_service_db`.`employee` (`id`, `cpf`, `email`, `name`, `password`, `role`) 
VALUES ('1', 'CPF_VALIDO', 'administrador@gmail', 'administrador', '$2a$12$MubpXWKG7s/nS/KBqxGS8.vNitLkESk1.Iiax2I4GpYr1ekfiXhxW', 'Administrador');
```
- Altere a segunda opção para um CPF válido, o login será feito com o CPF colocado no campo e com a senha: whatscode2022


### Etapa 5:
- Rodando o serviço do Front-End
- Em sua IDE execute o terminal utilize o seguinte comando dentro da pasta principal do projeto:
```
npm install
```
- Acesse a pasta src com seguinte comando:
```
cd src
```
- Execute o projeto com o seguinte comando:
```
npm run dev
```


### Etapa 6:
- Acesse o link fornecido no terminal para entrar na aplicação.

### Aplicação Funcionando
Pronto! A aplicação ja está rodando, caso tenha duvidas para a utilização, acesse:
[Manual de Utilização](https://github.com/whatscodeg3/API-3DSM/blob/main/doc/manuais/utilização.md)






