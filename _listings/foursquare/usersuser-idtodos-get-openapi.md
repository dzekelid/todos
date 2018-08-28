---
swagger: "2.0"
x-collection-name: Foursquare
x-complete: 0
info:
  title: Foursquare Get Users Todos
  description: /users/{USER_ID}/tips
  version: 1.0.0
host: api.foursquare.com
basePath: /v2/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /users/{USER_ID}/todos:
    get:
      summary: Get Users Todos
      description: /users/{USER_ID}/tips
      operationId: usersuser-idtips
      x-api-path-slug: usersuser-idtodos-get
      parameters:
      - in: query
        name: ll
        description: Latitude and longitude of the users location
      - in: query
        name: sort
        description: One of nearby or recent
      - in: query
        name: USER_ID
        description: Identity of the user to get todos for
      - in: path
        name: USER_ID
      - in: query
        name: v
        description: All requests now accept a v=YYYYMMDD param, which indicates that
          the client is up to date as of the specified date
      responses:
        200:
          description: OK
      tags:
      - Users
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