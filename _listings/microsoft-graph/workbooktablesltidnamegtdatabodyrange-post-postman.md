{
  "info": {
    "name": "Microsoft Graph API Table Data Body Range",
    "_postman_id": "850fd815-94e8-4f24-ac43-8f55732d1113",
    "description": "Table: DataBodyRange Gets the range object associated with the data body of the table.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "table",
      "item": [
        {
          "id": "e87ae60b-e6b7-4079-9d06-bea79f2edec9",
          "name": "Table:DataBodyRange",
          "request": {
            "url": "http://graph.microsoft.com/workbook/tables(&lt;id|name&gt;)/DataBodyRange",
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
              "id": "e67b7739-3793-4e16-9a31-4cbc5ecbea03"
            }
          ]
        }
      ]
    }
  ]
}