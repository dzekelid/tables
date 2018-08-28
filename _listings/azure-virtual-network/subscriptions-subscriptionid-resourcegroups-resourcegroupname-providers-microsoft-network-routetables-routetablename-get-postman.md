{
  "info": {
    "name": "Azure Virtual Network API Route Tables Get",
    "_postman_id": "c6a38365-00dc-439b-9b61-e20585c40fc4",
    "description": "Gets the specified route table.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "route tables",
      "item": [
        {
          "id": "919fc3a8-910c-4e95-9a33-3a309d4366bb",
          "name": "RouteTables_Get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Network/routeTables/:routeTableName"
              ],
              "query": [
                {
                  "key": "$expand",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "resourceGroupName",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "routeTableName",
                  "value": "{}",
                  "type": "string"
                },
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
            "description": "Gets the specified route table"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "272371b7-fbdf-41f9-93e7-8fc0fb4edced"
            }
          ]
        }
      ]
    }
  ]
}