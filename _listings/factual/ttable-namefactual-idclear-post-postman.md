{
  "info": {
    "name": "Factual Post Table Name Factual Clear",
    "_postman_id": "826bb923-1a8d-423c-9941-ed9c71272fce",
    "description": "Post table name factual clear.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Table",
      "item": [
        {
          "id": "f36e5f66-f1ab-4689-892d-3b3aeea490ae",
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
              "id": "2ee3031f-49e6-4f94-842b-050b1dcb0fa3"
            }
          ]
        },
        {
          "id": "39d55091-45da-4f97-a6f6-caaf785f79ea",
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
              "id": "c92061c9-8d98-45dc-8e88-b0f80311b4f6"
            }
          ]
        },
        {
          "id": "2a8d19a4-0a5a-4ee5-8e94-a3b0d4e53c7a",
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
              "id": "5144dec6-fbcd-437c-bab3-7e211b32be4b"
            }
          ]
        },
        {
          "id": "4dfba4cd-6ce0-4cf6-9fdb-effb15a4cd4f",
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
              "id": "a9460499-9869-4a51-958c-e9305c92de07"
            }
          ]
        },
        {
          "id": "ee241ef1-c523-4226-a44e-cd763271e5a7",
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
              "id": "9bf260da-1e2e-4f1e-bef1-e09a520f5739"
            }
          ]
        },
        {
          "id": "a1759aa1-250f-4108-8ee4-2c9eb7e7f5f7",
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
              "id": "cfd74997-da2e-4206-af28-ac2ce43a3820"
            }
          ]
        },
        {
          "id": "d3c9bf4a-18a9-4a6b-b6d3-f8056c566654",
          "name": "getTTableNameFactual",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.v3.factual.com",
              "path": [
                "t/:table_name/:factual_id"
              ],
              "variable": [
                {
                  "id": "factual_id",
                  "value": "{}",
                  "type": "string"
                },
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
            "description": "Get table name factual."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "76cc1bc8-3802-4491-84c7-f64405ee64c6"
            }
          ]
        },
        {
          "id": "5b50d416-8684-47bc-8966-1bdab19bf1b5",
          "name": "postTTableNameFactualClear",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.v3.factual.com",
              "path": [
                "t/:table_name/:factual_id/clear"
              ],
              "variable": [
                {
                  "id": "factual_id",
                  "value": "{}",
                  "type": "string"
                },
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
            "description": "Post table name factual clear."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "01e45cb9-8488-4c52-a69f-dfb61e009862"
            }
          ]
        }
      ]
    }
  ]
}