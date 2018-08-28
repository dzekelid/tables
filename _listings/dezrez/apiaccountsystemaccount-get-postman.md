{
  "info": {
    "name": "Dezrez Get System Account for the Accounting System",
    "_postman_id": "30fa2a9b-2313-4b5f-b9bb-fe6392ee3877",
    "description": "Get system account for the accounting system.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "System",
      "item": [
        {
          "id": "0fa20371-e58c-41ca-9826-1992ef9c6676",
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
              "id": "2900d2a1-c3df-43d2-a265-d496bf050113"
            }
          ]
        }
      ]
    }
  ]
}