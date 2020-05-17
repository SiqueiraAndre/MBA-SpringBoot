# SpringBoot
Projeto em Spring Boot com Java para a aula de Desenvolvimento JAVA na pós graduação

## Rotas de API

### GET - `/api/livro/list`
Retorna a lista de livros no padrão abaixo
```json
[
  {
    "title": "titulo",
    "pages": 200,
    "authorId": 1,
    "author": "Nome do autor",
    "evaluations": [
      {
        "comment": "Comentário",
        "note": 1
      }
    ]
  }
]
```
### GET - `/api/avaliacao/{id}`
Retorna os dados do livro passado no parâmetro de rota (`{id}`) na seguinte estrutura:
```json
[
  {
    "title": "titulo",
    "pages": 200,
    "authorId": 1,
    "author": "Nome do autor",
    "evaluations": [
      {
        "comment": "Comentário",
        "note": 1
      }
    ]
  }
]
```

> **Obs.:** A autenticação foi desenvolvida apenas para o sistema, as apis no momento permanescem públicas.
