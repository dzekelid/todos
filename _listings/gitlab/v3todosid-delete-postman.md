{
  "info": {
    "name": "GitLab Delete Todos",
    "_postman_id": "b0388ab7-5aa7-4e8d-88fa-0434f9298ef1",
    "description": "Mark a todo as done",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Todos",
      "item": [
        {
          "id": "767699c6-ecd4-4172-bed5-3915148a45ef",
          "name": "getV3Todos",
          "request": {
            "url": "http://localhost:3000/api/v3/todos?page=%7B%7D&per_page=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get a todo list"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1e8cf4ff-fcd0-40ee-b10f-c1ae763e550e"
            }
          ]
        },
        {
          "id": "a5311e57-0f78-4d8a-b8fa-f1c4b848d081",
          "name": "deleteV3Todos",
          "request": {
            "url": "http://localhost:3000/api/v3/todos",
            "method": "DELETE",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Mark all todos as done"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "776d6f88-5094-4e67-b480-c8d124c7a479"
            }
          ]
        },
        {
          "id": "8389d30d-9fb6-4aa5-9a15-ee043c6f07a5",
          "name": "deleteV3TodosId",
          "request": {
            "url": {
              "protocol": "http",
              "host": "localhost",
              "path": [
                "api",
                "v3/todos/:id"
              ],
              "port": "3000",
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Mark a todo as done"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "92c57648-97af-4479-8a55-96671637b9d0"
            }
          ]
        }
      ]
    }
  ]
}