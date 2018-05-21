{
  "info": {
    "name": "AWS EC2 API Describe Route Tables",
    "_postman_id": "5b0c8cad-a6aa-4566-ba58-c4a4bd6627d1",
    "description": "Describes one or more of your route tables.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Route Tables",
      "item": [
        {
          "id": "2d66c883-f2a9-4303-9cd6-904e5ad7a7d5",
          "name": "describeroutetables",
          "request": {
            "url": "http://example.com/api/?Action=DescribeRouteTables?GatewayId=GatewayId&RouteTableId=RouteTableId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your route tables."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2ad906a3-75f9-4bfb-b25d-be9cef8f886c"
            }
          ]
        }
      ]
    }
  ]
}