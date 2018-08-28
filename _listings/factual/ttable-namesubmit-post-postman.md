{
  "info": {
    "name": "Factual Post Table Name Submit",
    "_postman_id": "33562272-0a7a-492c-862e-1771667644a5",
    "description": "Post table name submit.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Table",
      "item": [
        {
          "id": "28ec168a-befd-452a-8b7e-e8decf697874",
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
              "id": "02bd999a-bf6a-4520-9514-9e2ec808f901"
            }
          ]
        },
        {
          "id": "e2c72862-04c7-4333-aefc-6fb4a49d10b2",
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
              "id": "424480b9-0aa1-4c0c-bf67-d6927d4151a4"
            }
          ]
        },
        {
          "id": "febede14-6816-4dfd-8252-7ad51d2bcac7",
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
              "id": "7e055cf3-fa96-4fd2-9708-148e95982e75"
            }
          ]
        },
        {
          "id": "96134b66-b089-4292-b57a-d53b10bd2936",
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
              "id": "aaba3d72-6b46-4240-a199-fe014ae6e516"
            }
          ]
        },
        {
          "id": "1cb4175c-6b82-4095-8386-f41b666b8f7d",
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
              "id": "0953f134-1a73-4b97-8092-263e3796e2a5"
            }
          ]
        },
        {
          "id": "b510aea8-435a-42c4-8d9f-cb9055c5c2c9",
          "name": "postTTableNameSubmit",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.v3.factual.com",
              "path": [
                "t/:table_name/submit"
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
            "description": "Post table name submit."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ee38b80e-e715-4d97-a2e3-a3a7e0e15162"
            }
          ]
        }
      ]
    }
  ]
}