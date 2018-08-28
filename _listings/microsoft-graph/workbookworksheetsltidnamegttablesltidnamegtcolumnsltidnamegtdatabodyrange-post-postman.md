{
  "info": {
    "name": "Microsoft Graph API Table Column Data Body Range",
    "_postman_id": "30399c40-e475-4d8f-a01a-1c70d6217e4f",
    "description": "TableColumn: DataBodyRange Gets the range object associated with the data body of the column.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "table",
      "item": [
        {
          "id": "99e23ccc-0c8f-45fe-a9a0-bf3ad6990c59",
          "name": "TableColumn:DataBodyRange",
          "request": {
            "url": "http://graph.microsoft.com/workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/DataBodyRange",
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
              "id": "50b2ac0b-c409-422e-bed3-de6e7bc9d5b1"
            }
          ]
        }
      ]
    }
  ]
}