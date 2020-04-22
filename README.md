# Curso de Angular 9

### Como Executar

- Entre na pasta [backend](./backend)
  - execute `yarn start` para executar o json-server

- Entre na pasta [frontend](./frontend)
- Execute `npm start`

### Dicas e anotações

- instalação da cli `sudo npm i -g @angular/cli`
- criando projeto `ng new nome_app --minimal`
  - minimal, vem sem testes
- adicionando estilo do material `ng add @angular/material`
- Criar componente: `ng generate component components/template/nome_componente` ou `ng g c components/template/nome_componente`
- Para exportar algum componente de lib tem de exportar no arquivo app.module.ts e adicionar em imports.

- mat-elevation-z4 da sensação de profundidade em componentes material


### configurações
- no documento angular.json mudar inlineTemplate e inlineStyle para false, com isso os componentes teram 3 arquivos , um do html, outro de ts e o de estilo