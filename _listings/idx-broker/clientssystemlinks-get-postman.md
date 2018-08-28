{
  "info": {
    "name": "IDX Broker Get System Links",
    "_postman_id": "546016b0-0b04-4693-a293-b1d533142478",
    "description": "Gathers all the pages system pages (search, featured, contact, etc) that can be directly linked to without additional property information being included in the URL.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "System",
      "item": [
        {
          "id": "a73aab45-0ae3-41ae-984a-3befb62d867c",
          "name": "ClientsSystemlinksGet",
          "request": {
            "url": "http://example.com/clients/systemlinks",
            "method": "GET",
            "header": [
              {
                "key": "accesskey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "ancillarykey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "apiversion",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "outputtype",
                "value": "{}",
                "description": "",
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
            "description": "Gathers all the pages system pages (search, featured, contact, etc) that can be directly linked to without additional property information being included in the URL."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "af45b1c1-98e5-4c04-ad0a-563680f9c67c"
            }
          ]
        }
      ]
    }
  ]
}