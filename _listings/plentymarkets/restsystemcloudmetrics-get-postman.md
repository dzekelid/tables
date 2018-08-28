{
  "info": {
    "name": "Plentymarkets Get the cloud metrics for this system",
    "_postman_id": "d9ee160b-7898-43fc-9253-b554e6771e40",
    "description": "Get the cloud metrics for this system.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Cloud",
      "item": [
        {
          "id": "9a512213-79fe-41f8-a7f5-04d20a63324e",
          "name": "getRestSystemCloudMetrics",
          "request": {
            "url": "http://example.com/rest/system/cloud/metrics",
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
            "description": "Get the cloud metrics for this system."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "795d270f-8cb7-4319-a367-18a1c6818223"
            }
          ]
        }
      ]
    }
  ]
}