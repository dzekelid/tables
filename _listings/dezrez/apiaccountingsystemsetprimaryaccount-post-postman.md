{
  "info": {
    "name": "Dezrez Set Primary Bank Account for Accounting System",
    "_postman_id": "bdafd201-2e1c-442c-95dc-20d8aefb2a3a",
    "description": "Set primary bank account for accounting system.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Set",
      "item": [
        {
          "id": "93c9a0ec-356d-4ce5-be44-e0e3ea4155f3",
          "name": "AccountingSystem_SetPrimarySystemBankAccountByid",
          "request": {
            "url": "http://api.dezrez.com/api/accountingsystem/setprimaryaccount?id=%7B%7D",
            "method": "POST",
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
            "description": "Set primary bank account for accounting system."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "be996a73-9afc-467e-9aee-c93a049cf537"
            }
          ]
        }
      ]
    }
  ]
}