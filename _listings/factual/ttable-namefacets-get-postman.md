{
  "info": {
    "name": "Factual Get Table Name Facets",
    "_postman_id": "84c64ed1-4ed0-4bde-977a-a2875ae02bab",
    "description": "Get table name facets.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Table",
      "item": [
        {
          "id": "eed09946-e7c2-44d2-b1d1-2a65818a2fdd",
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
              "id": "7df65713-19be-4a6e-802d-92492232482d"
            }
          ]
        },
        {
          "id": "8c3d9eeb-8ed2-495f-8eb0-3f4e709c41b4",
          "name": "getTTableNameFacets",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.v3.factual.com",
              "path": [
                "t/:table_name/facets"
              ],
              "variable": [
                {
                  "id": "table_name",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get table name facets."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9add1c89-c300-48a0-b663-e4c7618120a1"
            }
          ]
        }
      ]
    }
  ]
}