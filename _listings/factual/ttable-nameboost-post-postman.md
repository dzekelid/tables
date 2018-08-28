{
  "info": {
    "name": "Factual Post Table Name Boost",
    "_postman_id": "975f5629-0e27-4584-a939-b8e4c8cbac2e",
    "description": "Post table name boost.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Table",
      "item": [
        {
          "id": "38e7b55b-8984-4a84-bafa-e645c9943aa7",
          "name": "postTTableNameBoost",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.v3.factual.com",
              "path": [
                "t/:table_name/boost"
              ],
              "variable": [
                {
                  "id": "table_name",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Post table name boost."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5bcd17d5-8bbe-4605-86c3-85c452cef1ac"
            }
          ]
        }
      ]
    }
  ]
}