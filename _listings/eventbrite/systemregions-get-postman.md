{
  "info": {
    "name": "Eventbrite Get System Regions",
    "_postman_id": "99cbc7a1-a95a-44d0-89c5-f011e39c4d4e",
    "description": "Returns a single page response with a key of regions,\ncontaining a list of regions.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "System",
      "item": [
        {
          "id": "720d46cf-a6d0-4162-851c-302217a57d5e",
          "name": "getSystemRegions",
          "request": {
            "url": "http://www.eventbriteapi.com/v3/system/regions/",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a single page response with a key of regions,\ncontaining a list of regions."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d6d80f85-4031-41fd-ba30-09d490ac7153"
            }
          ]
        }
      ]
    }
  ]
}