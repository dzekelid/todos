{
  "info": {
    "name": "GitLab Get Todos",
    "_postman_id": "0eb6e54f-01fa-4d3a-acc6-2a55be83c89c",
    "description": "Get a todo list",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Todos",
      "item": [
        {
          "id": "eb103d30-3539-45bf-961e-e3f8ec08b6c4",
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
              "id": "a5859578-a72b-4437-b636-49b161033eb1"
            }
          ]
        }
      ]
    }
  ]
}