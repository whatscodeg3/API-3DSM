# API-3DSM

<p align="center">
      <img src="/doc/logo-whatscode.svg" alt="logo da equipe" width="200">
      <h3 align="center"> WhatsCode | Equipe 4</h3>

<hr>

<br>

<p align="center">
  <a href ="#api"> Aprendizagem por Projetos Integrados </a> |
  <a href ="#desafio"> Desafio </a>  |   
  <a href ="#repositorios"> Repositórios </a>  | 
  <a href ="#escopo"> Escopo do Projeto </a>  |
  <a href ="#bpmn"> BPMN </a>  |  
  <a href ="#backlog"> Backlog das Sprints </a>  | 
  <a href ="#manual"> Manual de Instalação e Utilização  |
  <a href ="#sprint"> Sprints </a>  | 
  <a href ="#equipe"> Equipe </a>  |
</p>

<br>

<h4 align="center">
 <a href="https://reactjs.org/docs/getting-started.html"><img src = "https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/></a>
 <a href="https://dev.java/learn/"><img src = "https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white"/></a>
 <a href="https://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/"><img src = "https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white"/></a>
 <a href="https://www.typescriptlang.org"><img src = "https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white"/></a>
 <a href="https://dev.mysql.com/doc/"><img src = "https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white"/></a>
 <a href="https://docs.docker.com"><img src = "https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/></a>
</h4>

<br>

> Status do Projeto: Em Desenvolvimento
> <br>

## Aprendizagem por Projetos Integrados <a id="api"></a>

A API (Aprendizagem por Projetos Integrados), desenvolvida no escopo do CADI, é a metodologia de ensino em implantação na Fatec São José dos Campos, desde o Segundo Semestre de 2019, do qual os alunos formam equipes baseadas na metodologia scrum, tendo um aluno como master, Product Owner e os integrates restantes dev team. O time é desafiado por um cliente real (nesse projeto nosso cliente é a Pro4Tech), a desenvolver uma solução para um problema, tendo que atender requisitos exigidos de tecnologia. <br>

O API segue tendo como pilares os seguintes valores: <br>
 - Real Problem Based Learning (rPBL) <br>
 - Validação Externa <br>
 - Mindset Ágil (Agile) <br>

<br>

## :pencil2: Desafio <a id="desafio"></a>

Uma empresa tem problema na gestão de cobranças. Eles precisam de uma solução que permita o cadastro de clientes, registro de cobranças das parcelas a receber e dos pagamentos efetuados, além da geração de relatórios de cobrança com diferentes tipos de busca por data e situação das parcelas.
<br>

Proposta: Desenvolver um sistema em microsserviços que permite com que os funcinários da empresa consigam cadastrar vendas e ter controle sobre as parcelas a serem pagas por seus clientes, gerando relatórios completos para facilitar a análise de informações.

<br>

## :file_folder: Repositórios <a id="repositorios"></a>

Optamos por utilizar um total de 4 repositórios para o projeto, sendo esse como o principal, com todos os repositórios linkados como sub-módulos, um repósitorio destinado ao front-end, e dois repositórios destinados ao back-end, separados por microsserviços.

Para acessar todos os repositórios utilize a ligação do repositório principal, ou acesse pelos seguintes links:

·Repositório Principal: https://github.com/whatscodeg3/API-3DSM <br>

·Repositório Front-End: https://github.com/whatscodeg3/API-3DSM-Frontend <br>

·Repositório Back-End-Client: https://github.com/whatscodeg3/API-3DSM-Backend-Client <br>

·Repositório Back-End-Purchases: https://github.com/whatscodeg3/API-3DSM-Backend-Purchases <br>

## :dart: Escopo do Projeto <a id="escopo"></a>

> _Requisitos Funcionais_

· Cadastro de clientes. <br>

· Registro de parcelas a vencer. <br>

· Registro de baixas de parcelas. <br>

· Gerar relatórios de cobrança. <br>
<br>

> _Requisitos Não Funcionais_

· Documentação com mapeamento das regras de negócio do cliente. <br>

· Java. <br>

· TypeScript. <br>

· BPMN a ser apresentado na primeira Sprint. <br>
<br>

> _Tecnologias Desejáveis_

· MySQL. <br>
<br>

<br>

## :scroll: BPMN (Business Process Model and Notation): <a id="bpmn"> </a>

O BPMN é uma notação da metodologia de gerenciamento de processos de negócio e trata-se de uma série de ícones padrões para o desenho de processos, o que facilita o entendimento do usuário.

•BPMN Cadastro de Cliente : <br>
[Acessar Imagem](https://github.com/whatscodeg3/API-3DSM/blob/main/doc/img/BPMN_cadastroCliente.PNG)
<img src="/doc/img/BPMN_cadastroCliente.PNG" alt="BPMN Cadastro Cliente" width="3000">

•BPMN Cadastro de Venda : <br>
[Acessar Imagem](https://github.com/whatscodeg3/API-3DSM/blob/main/doc/img/BPMN_cadastroVenda.PNG)
<img src="/doc/img/BPMN_cadastroVenda.PNG" alt="BPMN Cadastro Venda" width="3000">

•BPMN Gerar Relatório : <br>
[Acessar Imagem](https://github.com/whatscodeg3/API-3DSM/blob/main/doc/img/BPMN_gerandoRelatorio.PNG)
<img src="/doc/img/BPMN_gerandoRelatorio.PNG" alt="BPMN Gerando Relatorio" width="3000">

<br>

## :bookmark_tabs: Backlog Total e Historias de Usuário <a id="backlog"></a>

| Prioridade |                                                        User Stories                                                        |                                                     Critério de Aceitação                                                      | Sprint | Status |
| :--------: | :------------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------: | :----: | :----: |
|  Alta 🟥   |                   Eu como um usuário gostaria de uma funcionalidade que permita o cadastro de clientes.                    |                       Tem como valor o armazenamento de dados do clientes para gerenciar os pagamentos.                        |   1    |   ✅   |
|  Alta 🟥   | Eu como um usuário gostaria de uma funcionalidade que permita o registro de vendas que automaticamente gere suas parcelas. |                     Tem como valor armazenar as vendas e gerar suas parcelas para controle de pagamentos.                      |   1    |   ✅   |
|  Alta 🟥   |                Eu como usuário gostaria de um registro das vendas cadastradas e suas respectivas parcelas.                 |                                      Tem como valor identificar as vendas já cadastradas.                                      |   1    |   ✅   |
|  Alta 🟥   |                   Eu como usuário gostaria de um registro de baixas de parcelas realizadas pelo cliente.                   |                               Tem como valor identificar rapidamente os clientes inadimplentes.                                |   2    |   ✅   |
|  Alta 🟥   |                            Eu como usuário gostaria de gerar um relatório completo de cobrança.                            | Tem como valor visualizar as informações importantes sobre as parcelas de meus clientes, facilitando a análise de informações. |   2    |   ✅   |
|  Média 🟨  |        Eu como administrador gostaria de cadastrar funcionários para o sistema como um financeiro ou um comercial.         |                           Tem como valor distribuir as funções dos empregados na empresa no sistema                            |   3    |   ✅   |
|  Média 🟨  |                      Eu como administrador gostaria que o sistema possua um controle de permissões .                       |                           Tem como valor distribuir as funções dos empregados na empresa no sistema                            |   4    |   🔄   |
|  Baixa 🟩  |  Eu como administrador gostaria que as informações fossem passadas para o banco de dados fora do horário de expediente .   |                            Tem como valor não sobrecarregar o sistema gerando a perda de algum dado                            |   4    |   🔄   |

<br>

## :clipboard: Manual de Instalação e Utilização <a id="manual"></a>

Manual de instalação: ([Acessar Manual de Instalação](https://github.com/whatscodeg3/API-3DSM/blob/main/doc/manuais/instalação.md))

Manual de Utilização: ([Acessar Manual de Utilização](https://github.com/whatscodeg3/API-3DSM/blob/main/doc/manuais/utilização.md))

<br>

## :date: Sprints <a id="sprint"></a>

🔖 SPRINT 1 : ([Relatório da Sprint](https://github.com/whatscodeg3/API-3DSM/tree/main/doc/sprints/Sprint%201)) ✅

🔖 SPRINT 2 : ([Relatório da Sprint](https://github.com/whatscodeg3/API-3DSM/tree/main/doc/sprints/Sprint%202)) ✅

🔖 SPRINT 3 : ([Relatório da Sprint](https://github.com/whatscodeg3/API-3DSM/tree/main/doc/sprints/Sprint%203)) ✅

🔖 SPRINT 4 : ([Relatório da Sprint](https://github.com/whatscodeg3/API-3DSM/tree/main/doc/sprints/Sprint%204)) 🔄

<br>

## :mortar_board: Equipe <a id="equipe"></a>

|     Membro      |    Função     |                                                                        Github                                                                         |                                                                                             Linkedin                                                                                             |
| :-------------: | :-----------: | :---------------------------------------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| Matheus Augusto | Scrum Master  | <a href="https://github.com/MatheusAJesus"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a> | <a href="https://www.linkedin.com/in/matheus-augusto-de-jesus-albernaz-918536216"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> |
|  Lucas Medici   | Product Owner |  <a href="https://github.com/LucasMedici"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>  |           <a href="https://www.linkedin.com/in/lucas-medici-a15971237"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>            |
| Thiago Oliveira | Desenvolvedor |   <a href="https://github.com/ThiagoOAL"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>   |               <a href="https://www.linkedin.com/in/thiagoleite042"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>                |
|  Kevin Ribeiro  | Desenvolvedor |  <a href="https://github.com/KevinRomRib"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>  |                 <a href="https://www.linkedin.com/in/kevinrribeiro/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">                  |
|  Jonatas Dallo  | Desenvolvedor | <a href="https://github.com/Jonatas-Dallo"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a> |         <a href="https://www.linkedin.com/in/jonatas-mathias-147638206/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>          |
|   Pedro Corrá   | Desenvolvedor |    <a href="https://github.com/PHCorra"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>    |             <a href="https://www.linkedin.com/in/pedro-c-95b57212a/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>              |
