{
  "info": {
    "name": "Factual Get Table Name Schema",
    "_postman_id": "10141535-519d-4ffa-81ea-d3660ee3fd24",
    "description": "Get table name schema.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Table",
      "item": [
        {
          "id": "b141494b-0d2b-4e98-b784-ff84cb8eaa81",
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
              "id": "a21860e1-0ee0-43bd-b5df-d04ef5c0b8bd"
            }
          ]
        },
        {
          "id": "38c78a44-0227-46c4-b48f-c6bdb88cb967",
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
              "id": "71af3a42-d3ba-4ac0-956f-d33257bb72c2"
            }
          ]
        },
        {
          "id": "dc13a293-f965-44e7-8b55-18e5ee68e63b",
          "name": "getTTableNameMatch",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.v3.factual.com",
              "path": [
                "t/:table_name/match"
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
            "description": "Get table name match."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fba7b4aa-d600-4ab6-8dd8-aceee4fe334e"
            }
          ]
        },
        {
          "id": "92a79476-f5eb-49ec-92df-16749ea21e5f",
          "name": "getTTableNameResolve",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.v3.factual.com",
              "path": [
                "t/:table_name/resolve"
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
            "description": "Get table name resolve."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "688c898c-45b0-4eeb-9f72-67c533fdc464"
            }
          ]
        },
        {
          "id": "56c6676b-357d-4cef-aa9a-36d99dbcf863",
          "name": "getTTableNameSchema",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.v3.factual.com",
              "path": [
                "t/:table_name/schema"
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
            "description": "Get table name schema."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "31413d2b-e6fe-4973-b0d0-2dd92c4b5060"
            }
          ]
        }
      ]
    }
  ]
}