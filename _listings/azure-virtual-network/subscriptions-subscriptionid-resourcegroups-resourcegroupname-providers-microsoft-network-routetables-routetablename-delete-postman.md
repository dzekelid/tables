{
  "info": {
    "name": "Azure Virtual Network API Route Tables Delete",
    "_postman_id": "3bc91c4b-cb19-4641-8238-22b2585cc277",
    "description": "Deletes the specified route table.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "route tables",
      "item": [
        {
          "id": "cbf9357e-ce69-4352-bc38-24f648c62f48",
          "name": "RouteTables_Delete",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Network/routeTables/:routeTableName"
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
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified route table"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1325317a-6e9b-443e-afd4-3207b2a2cc3d"
            }
          ]
        }
      ]
    }
  ]
}