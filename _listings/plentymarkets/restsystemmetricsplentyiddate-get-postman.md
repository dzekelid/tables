{
  "info": {
    "name": "Plentymarkets Supply usage data for given plentymarkets system",
    "_postman_id": "d049770e-38b5-4340-b9ff-18137a05d809",
    "description": "Supply usage data for given plentymarkets system.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Supply",
      "item": [
        {
          "id": "646d17a0-9588-4b5d-88ee-d6bf91641c72",
          "name": "getRestSystemMetricsPlentyDate",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/system/metrics/:plentyId/:date"
              ],
              "variable": [
                {
                  "id": "date",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "plentyId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
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
            "description": "Supply usage data for given plentymarkets system."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7fc76c2c-42a3-4bc3-8137-d78c5410cfb3"
            }
          ]
        }
      ]
    }
  ]
}