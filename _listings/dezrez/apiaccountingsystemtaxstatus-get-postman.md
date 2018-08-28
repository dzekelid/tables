{
  "info": {
    "name": "Dezrez Get Tax Status of Accounting System",
    "_postman_id": "57fa96a8-9a19-45ec-83ff-a3bf876aa085",
    "description": "Get tax status of accounting system.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "System",
      "item": [
        {
          "id": "43d792c7-a59f-43f9-aba1-42823222378b",
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
              "id": "d6cd6709-10a5-4801-8d04-252032826895"
            }
          ]
        }
      ]
    },
    {
      "name": "S",
      "item": [
        {
          "id": "cb0e5ef7-45ab-4f0c-98e1-c44c4f389ad4",
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
              "id": "9329f3de-d1a9-456b-b0da-fb7bbefd89bd"
            }
          ]
        },
        {
          "id": "fbae01b3-bef3-4bef-a03e-6ecee68bb59b",
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
              "id": "037d9f1b-4c5d-4ca6-896f-ecc7d08ca538"
            }
          ]
        }
      ]
    },
    {
      "name": "Archives",
      "item": [
        {
          "id": "cc98c720-5adb-4ed2-a97d-ffb49f0779ff",
          "name": "AccountingSystem_ArchiveSystemByforce",
          "request": {
            "url": "http://api.dezrez.com/api/accountingsystem/systembalance?force=%7B%7D",
            "method": "PUT",
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
            "description": "Archives the accounting system."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4ef82317-ab53-4eac-8c98-75426e6ea613"
            }
          ]
        }
      ]
    },
    {
      "name": "Tax",
      "item": [
        {
          "id": "176117a2-00ca-4d6f-b268-0e7a987804fa",
          "name": "AccountingSystem_GetTaxStatus",
          "request": {
            "url": "http://api.dezrez.com/api/accountingsystem/taxstatus",
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
            "description": "Get tax status of accounting system."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5b9ecc1c-5ffe-419d-bc58-0f792519e4c0"
            }
          ]
        }
      ]
    }
  ]
}