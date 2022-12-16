Aula 01 - Fundamentos do Nest.js & Prisma - Ignite Lab Node.js

Nessa aula vamos realizar o setup do nosso projeto conhecendo as particularidades do framework NestJS integrado ao Prisma como ORM. Vamos dar início a estrutura do projeto criando nossa primeira rota com acesso ao banco de dados.

ANOTAÇÕES

MICROSSERVIÇO:
- Uma aplicação onde as suas funcionalidades são separadas em projetos menores que, apesar de interligados, são independentes.

Nest.JS:
- O NestJS é um framework opinado que apesar de seguir princípios do SOLID, permite uma customização na estrutura do seu projeto;
- O NestJS é construído desde a sua primeira versão com Typescript, sendo assim ele possui um excelente suporte às tipagens e funcionalidades mais avançadas do Typescript como decorators;
- O NestJS traz diversas recipes de ferramentas muito utilizadas no mercado, como o Prisma, facilitando muito o uso delas na aplicação;
- Arquivos principais na pasta 'src': Modules, controllers e services.

PRISMA:
- O Prisma é um ORM que auxilia no gerenciamento de diversos tipos de bancos de dados, como SQLite e Cockroach;
- O Prisma possui o Studio, uma ferramenta que possibilita a visualização das tabelas e registros do banco de dados diretamente pelo navegador;
- O Prisma consegue criar as migrations a partir dos Models definidos pelo desenvolvedor, facilitando assim o gerenciamento e versionamento do banco de dados.


Aula 02 - Domínio, casos de uso e regras de negócio - Ignite Lab Node.js

Nessa aula vamos utilizar uma abordagem de DESIGN DE SOFTWARE para definir o domínio da nossa aplicação, suas entidades, casos de uso e regras de negócio. Vamos também conhecer princípios importantes do SOLID como a inversão de dependências e criar nossos primeiros testes automatizados.

ANOTAÇÕES

GETTERS e SETTERS:
 - Para adicionarmos uma camada de proteção no gerenciamento dos nossos dados, utilizaremos getters e setters na nossa classe Notification. Os getters e setters permitem que a gente busque e configure dados por meio de métodos definidos, podendo assim aplicar validações e outras proteções em vez de simplesmente aceitar os valores repassados.

 VALUE OBJECT:
 - Uma forma de agregar validações e outras funcionalidades no momento da definição de um campo.

 TESTES:
 - Testes unitários são uma forma de testar um trecho específico de um arquivo do código, ou seja, tem um escopo bem definido e é normalmente independente de outras partes da aplicação.
 - Testes de integração são testes maiores e mais complexos, que tendem a testar um fluxo inteiro como, por exemplo, a autenticação de um usuário.
 - TDD é um conceito que se refere a como desenvolvemos uma aplicação: guiada pelos testes. Ou seja, os testes são normalmente criados antes das funcionalidades.

 IN-MEMORY DATABASE:
 - Trabalhar com os dados no mesmo padrão e formato do banco de dados em produção, porém mantendo os dados apenas em memória. Assim, evita a dependência de terceiros nos testes (banco de dados) e também do uso de mocks.


Aula 03 - Infraestrutura e injeção de dependências - Ignite Lab Node.js
Nessa aula vamos conectar todas camadas da nossa aplicação para se conversarem entre si criando rotas, controllers, validações, além de trabalhar com o conceito de injeção de dependência do NestJS. Aqui vamos também finalizar alguns testes e conhecer o conceito de factory.

ANOTAÇÕES

