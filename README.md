# Yorgut
# Descrição do projeto
O projeto consiste em uma nova maneira invadora e única de se comunicar com as pessoas. Algo nunca feito e nunca pensado antes, algo como um rede de socialização entre pessoas na internet. Onde pessoas que não se conhecem podem saber o que você está pensando e você pode saber o que pessoas que você não conhece estão pensando. Uma maneira de (principalmente agora em pandemia) aumentar o distanciamento social, uma vez que não precisaremos mais nos encontrar para nos comunicarmos.

Cada usuário terá sua própria *home page* que apenas ele tera a possibilidade de edição, e tudo o que ele postar será publicado nesta rede de forma que qualquer pessoa poderá ver todas as publicações de todos que estão na rede. Todas as *home pages* dos usuário estárão disponíveis através de um link que qualquer pessoa (desde que esteja logada) possa acessar. 

# Proposta do projeto (especificações técnicas)  
## Gestão de usuários
Para a gestão de usuários serão implementadas as seguintes *features*:
* Fluxo de esqueci minha senha;
* Integração com autenticação pelo *Facebook* e *Gmail* através da API **OAuth**;
* Será possível que o usuário altere informações como nome, foto e outras informações que desejar.

## Engenharia de Software
* Integração contínua durante o desenvolvimento (através da plataforma **Heroku** + **GitHub**);

## Integração

## Inteligência

## BackEnd
* Agendamento de funções do *BackEnd* para atualização das postagens dos usuários
* Camada de dados RESTful
* Upload de arquivos *(?)*

## FrontEnd
* Todas as páginas responsivas
* Organização em componentes


## Tecnologias utilizadas
Neste tópico serão listadas quais as tecnologicas foram escolhidas para o desenvolvimento do sistema
* **FrontEnd**: Para o FrontEnd a framework escolhida foi o **Angular 8**
* **BackEnd**: O BackEnd será desenvolvido em **NodeJS**
* **Servidor**: Tanto o FrontEnd quanto o BackEnd serão hospedados na plataforma em nuvem **Heroku**
* **Banco de Dados**: O Banco de dados utilizado será o **MongoDB** com uma instância hosperada no servidor da **Atlas**