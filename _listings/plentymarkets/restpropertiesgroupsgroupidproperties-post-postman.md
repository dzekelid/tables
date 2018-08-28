{
  "info": {
    "name": "Plentymarkets Mass attach propertyId and groupId collection into the pivot table.",
    "_postman_id": "eb8b3271-b647-4292-819c-b2b8cd94229b",
    "description": "Mass attach propertyid and groupid collection into the pivot table..",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Mass",
      "item": [
        {
          "id": "75fe8e31-c19b-425c-9ef3-b16300cf1395",
          "name": "postRestPropertiesGroupsGroupProperties",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/properties/groups/:groupId/properties"
              ],
              "variable": [
                {
                  "id": "groupId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Mass attach propertyid and groupid collection into the pivot table.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "522433cc-6025-450a-950e-05801ba94311"
            }
          ]
        }
      ]
    }
  ]
}