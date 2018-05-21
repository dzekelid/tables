{
  "info": {
    "name": "Azure Virtual Network API Route Tables List All",
    "_postman_id": "07bf78bf-f2e1-4979-9b4c-12432a2f29a9",
    "description": "Gets all route tables in a subscription.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "route tables",
      "item": [
        {
          "id": "fde13cca-a609-43cf-a519-83c781c68fa4",
          "name": "RouteTables_ListAll",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/providers/Microsoft.Network/routeTables"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "subscriptionId",
                  "value": "subscriptionId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets all route tables in a subscription"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f090c3c0-cc9c-4a5d-ae2f-c368657fd023"
            }
          ]
        }
      ]
    }
  ]
}