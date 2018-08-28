{
  "info": {
    "name": "Dezrez Gets accounting system balance",
    "_postman_id": "db93b64b-bbf6-46ad-b0a6-ec4549bc233a",
    "description": "Gets accounting system balance.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "System",
      "item": [
        {
          "id": "e37a805b-8931-47b6-bb15-ef643077dcb2",
          "name": "Account_GetSystemAccount",
          "request": {
            "url": "http://api.dezrez.com/api/account/systemaccount",
            "method": "GET",
            "header": [
              {
                "key": "Rezi-Api-Version",
                "value": "{}",
                "description": "Specifies which version of the API to call",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get system account for the accounting system."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "097c51bd-caed-4840-9ba1-e27a43835350"
            }
          ]
        }
      ]
    },
    {
      "name": "S",
      "item": [
        {
          "id": "70cfc642-b14c-4c5e-b076-7a6d36165c70",
          "name": "AccountingSystem_Get",
          "request": {
            "url": "http://api.dezrez.com/api/accountingsystem",
            "method": "GET",
            "header": [
              {
                "key": "Rezi-Api-Version",
                "value": "{}",
                "description": "Specifies which version of the API to call",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets accounting system for a legal entity."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "684a779a-a085-469e-9f63-bd0051f27d40"
            }
          ]
        },
        {
          "id": "74ade987-bdc8-44e4-8cfe-a9cfec1897c3",
          "name": "AccountingSystem_GetSystemBalance",
          "request": {
            "url": "http://api.dezrez.com/api/accountingsystem/systembalance",
            "method": "GET",
            "header": [
              {
                "key": "Rezi-Api-Version",
                "value": "{}",
                "description": "Specifies which version of the API to call",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets accounting system balance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d6b4a39f-354c-4fb1-86b6-ff17643499ca"
            }
          ]
        }
      ]
    }
  ]
}