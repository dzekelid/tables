{
  "info": {
    "name": "Factual Get Table Name Factual",
    "_postman_id": "a6f60d8f-8029-4230-87ac-160fd4bb8a32",
    "description": "Get table name factual.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Table",
      "item": [
        {
          "id": "1bcb6e22-ef9a-42db-80af-bde8c2ca660f",
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
              "id": "07f71145-8ffa-4087-a174-b2162deb60af"
            }
          ]
        },
        {
          "id": "81c4e8d2-f97a-46a2-a370-28c9e872b3a4",
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
              "id": "12903fa4-7199-4a46-93de-9924a2045662"
            }
          ]
        },
        {
          "id": "688dcadd-e36f-4b0e-a84c-32c84b44f19e",
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
              "id": "3aac1832-e432-4654-8389-80a07b8a25a0"
            }
          ]
        },
        {
          "id": "b2554c48-dc83-4bba-97de-40831839f424",
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
              "id": "51cd87ee-4152-4ffc-a962-788d1f1646cb"
            }
          ]
        },
        {
          "id": "25fa68c4-18ba-49a2-8c8c-9d3a57f51036",
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
              "id": "393fae81-c1af-4acd-b710-c074ec44b22a"
            }
          ]
        },
        {
          "id": "bf3314f2-1303-46d4-89fc-ec20c2de55f0",
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
              "id": "65f0d855-1df9-4baf-861a-e9628eac3680"
            }
          ]
        },
        {
          "id": "1c17488d-e346-4b14-9c64-e160501b19b6",
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
              "id": "2d47f869-9184-459d-91c9-355d6f482b27"
            }
          ]
        }
      ]
    }
  ]
}