{
  "info": {
    "name": "Azure Virtual Network API Route Tables List",
    "_postman_id": "8decfcac-4ae5-4720-8bca-60f96b9cfb15",
    "description": "Gets all route tables in a resource group.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "route tables",
      "item": [
        {
          "id": "e255dbd0-3729-4751-a862-b8c44d16cea5",
          "name": "RouteTables_List",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Network/routeTables"
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
                  "id": "resourceGroupName",
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
            "description": "Gets all route tables in a resource group"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "02b23a6e-7cd0-44dd-b9ae-9ab3e7b55aab"
            }
          ]
        }
      ]
    }
  ]
}