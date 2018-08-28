{
  "info": {
    "name": "Factual Get Table Name Match",
    "_postman_id": "40c7dc3c-9c91-4e43-930e-25c3e9e36e27",
    "description": "Get table name match.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Table",
      "item": [
        {
          "id": "fde45754-f586-4a68-b9d7-f09d9a3a0124",
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
              "id": "d4f3e635-e270-47b6-a4fe-14f9ca3c572e"
            }
          ]
        },
        {
          "id": "1886033f-b6cb-4cf9-9fc4-21018c97239a",
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
              "id": "300fa788-5424-4168-a054-d8487bc8567b"
            }
          ]
        },
        {
          "id": "699e43c6-ecfb-445f-9e38-fcf877b1adca",
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
              "id": "023c498f-77d5-4b06-bf88-2c05d8e63aa1"
            }
          ]
        }
      ]
    }
  ]
}