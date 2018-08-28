---
swagger: "2.0"
x-collection-name: GitLab
x-complete: 0
info:
  title: GitLab Delete Todos
  version: 1.0.0
  description: Mark all todos as done
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
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---