swagger: "2.0"
x-collection-name: Foursquare
x-complete: 1
info:
  title: Foursquare
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