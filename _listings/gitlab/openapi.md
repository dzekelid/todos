---
swagger: "2.0"
x-collection-name: GitLab
x-complete: 1
info:
  title: API title
  version: 1.0.0
host: localhost:3000
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v3/todos:
    get:
      summary: Get Todos
      description: Get a todo list
      operationId: getV3Todos
      x-api-path-slug: v3todos-get
      parameters:
      - in: query
        name: page
        description: Current page number
      - in: query
        name: per_page
        description: Number of items per page
      responses:
        200:
          description: OK
      tags:
      - Todos
    delete:
      summary: Delete Todos
      description: Mark all todos as done
      operationId: deleteV3Todos
      x-api-path-slug: v3todos-delete
      responses:
        200:
          description: OK
      tags:
      - Todos
  /v3/todos/{id}:
    delete:
      summary: Delete Todos
      description: Mark a todo as done
      operationId: deleteV3TodosId
      x-api-path-slug: v3todosid-delete
      parameters:
      - in: path
        name: id
        description: The ID of the todo being marked as done
      responses:
        200:
          description: OK
      tags:
      - Todos
---