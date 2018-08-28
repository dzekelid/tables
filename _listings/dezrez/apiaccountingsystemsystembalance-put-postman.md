{
  "info": {
    "name": "Dezrez Archives the accounting system",
    "_postman_id": "f3f105aa-e3c9-4608-8da8-acd78ecb0351",
    "description": "Archives the accounting system.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "System",
      "item": [
        {
          "id": "7dde5ec2-b276-4667-8881-e5a51f9604a0",
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
              "id": "152b272c-308e-4fa5-9cd2-eb89eb1abc10"
            }
          ]
        }
      ]
    },
    {
      "name": "S",
      "item": [
        {
          "id": "5798f63b-5721-4481-a066-4d246f129f2b",
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
              "id": "4ca74682-795e-4f7f-9b1f-c392b81fd12b"
            }
          ]
        },
        {
          "id": "ca9d9cf5-d35e-44d8-a5f0-6ba07a9b4012",
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
              "id": "8f176c5e-257f-47cd-b0b4-7c67f9148f1e"
            }
          ]
        }
      ]
    },
    {
      "name": "Archives",
      "item": [
        {
          "id": "30e8861e-dfe3-40cd-807a-f94889846eb4",
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
              "id": "10a6512c-eeee-43cb-af86-f8fdbd7ec12c"
            }
          ]
        }
      ]
    }
  ]
}