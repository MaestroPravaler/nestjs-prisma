<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

[circleci-image]: https://img.shields.io/circleci/build/github/nestjs/nest/master?token=abc123def456
[circleci-url]: https://circleci.com/gh/nestjs/nest


## Descrição

Realização de um crud Simples para a fixação de conhecimentos em NestJS e Prisma..

## Para Rodar o Projeto

```bash
$ npm run start:dev
```

## Verificação das funcionalidades com o Postman

1. Criar um Registro (METODO: POST) - http://localhost:3000/books

```json
    {
    "title" : "Domain Driven Design",
    "description": "Livro destinado a quem deseja aprender DDD",
    "bar_code": "43553456123212765435"
}
 ```

2. Listar todos os Registros (METODO: GET) - http://localhost:3000/books

3. Atualizar um Registro (METODO: PUT) - http://localhost:3000/books/{{:id}}

```json
    {
    "title" : "Domain Driven Design (Alterado)",
    "description": "Livro destinado a quem deseja aprender DDD",
    "bar_code": "43553456123212765435"
}
 ```

4. Deletar um Registro (METODO: DELETE) - http://localhost:3000/books/{{:id}}




