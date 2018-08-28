{
  "info": {
    "name": "GitLab Delete Todos",
    "_postman_id": "62ffc862-cd1f-4be0-bfba-b9523983f9d0",
    "description": "Mark all todos as done",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Todos",
      "item": [
        {
          "id": "34a762f0-4506-4cdb-ab30-d9882376f175",
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
              "id": "67cc9605-ae34-4105-b014-47c070acb863"
            }
          ]
        },
        {
          "id": "d2508bfe-0161-44b1-a874-f8c3fb75f156",
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
              "id": "d20011bd-8ee3-43ca-b614-07d222be946e"
            }
          ]
        }
      ]
    }
  ]
}