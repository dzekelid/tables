{
  "info": {
    "name": "Microsoft Graph API Table Data Body Range",
    "_postman_id": "2e24c813-98d3-4e40-9246-fddad6804ca1",
    "description": "Table: DataBodyRange Gets the range object associated with the data body of the table.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "table",
      "item": [
        {
          "id": "6fbbec36-6972-4180-91c5-0dcd54f649c6",
          "name": "Table:DataBodyRange",
          "request": {
            "url": "http://graph.microsoft.com/workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/DataBodyRange",
            "method": "POST",
            "header": [
              {
                "key": "Authorization",
                "value": "{}",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Table: DataBodyRange Gets the range object associated with the data body of the table"
          },
          "response": [
            {
              "code": 200,
              "name": "Response_200",
              "id": "6d676956-21e6-44c1-a6b3-76fc5b5dd56b"
            }
          ]
        }
      ]
    }
  ]
}