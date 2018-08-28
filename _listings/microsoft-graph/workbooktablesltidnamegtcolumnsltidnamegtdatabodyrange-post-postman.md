{
  "info": {
    "name": "Microsoft Graph API Table Column Data Body Range",
    "_postman_id": "b13d08a4-ad81-4ad9-b868-eada29b891ee",
    "description": "TableColumn: DataBodyRange Gets the range object associated with the data body of the column.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "table",
      "item": [
        {
          "id": "e1efc5f8-10c8-4d93-a3ac-5941291cfbb0",
          "name": "TableColumn:DataBodyRange",
          "request": {
            "url": "http://graph.microsoft.com/workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/DataBodyRange",
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
            "description": "TableColumn: DataBodyRange Gets the range object associated with the data body of the column"
          },
          "response": [
            {
              "code": 200,
              "name": "Response_200",
              "id": "9ba6abb0-6b08-4d6a-8646-7e35ee7735f2"
            }
          ]
        }
      ]
    }
  ]
}