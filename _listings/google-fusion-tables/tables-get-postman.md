{
  "info": {
    "name": "Google Fusion Tables API Get Tables",
    "_postman_id": "28dd04cb-fd71-4cc2-8552-81f7211e5b1b",
    "description": "Retrieves a list of tables a user owns.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Query",
      "item": [
        {
          "id": "7615b7a8-ee55-47ac-871a-26f60a2cc789",
          "name": "fusiontables.query.sqlGet",
          "request": {
            "url": "http://www.googleapis.com/fusiontables/v2/query?hdrs=%7B%7D&sql=%7B%7D&typed=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Executes a SQL statement which can be any of \n- SELECT\n- SHOW\n- DESCRIBE"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "68efda9d-e48e-4d83-941c-881901c1a320"
            }
          ]
        },
        {
          "id": "4cf905c1-080a-419b-ab37-4ab4776e6878",
          "name": "fusiontables.query.sql",
          "request": {
            "url": "http://www.googleapis.com/fusiontables/v2/query?hdrs=%7B%7D&sql=%7B%7D&typed=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Executes a Fusion Tables SQL statement, which can be any of \n- SELECT\n- INSERT\n- UPDATE\n- DELETE\n- SHOW\n- DESCRIBE\n- CREATE statement."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fc7be221-debe-424a-9b88-20eff7ebe8df"
            }
          ]
        }
      ]
    },
    {
      "name": "Table",
      "item": [
        {
          "id": "83d4fbdb-79bd-4256-8e3b-1af6ce3057b2",
          "name": "fusiontables.table.list",
          "request": {
            "url": "http://www.googleapis.com/fusiontables/v2/tables?maxResults=%7B%7D&pageToken=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves a list of tables a user owns."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f70b3216-33a1-4bfb-931e-612ab9e2f485"
            }
          ]
        }
      ]
    }
  ]
}