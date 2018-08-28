{
  "info": {
    "name": "Microsoft Graph API Table Clear Filters",
    "_postman_id": "74ece0ab-52be-4bbf-9571-4223fb9bab17",
    "description": "Table: clearFilters Clears all the filters currently applied on the table.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Table",
      "item": [
        {
          "id": "26d7a849-badb-44b0-bfa0-9334c24fbaa9",
          "name": "Table:ClearFilters",
          "request": {
            "url": "http://graph.microsoft.com/workbook/tables(&lt;id|name&gt;)/clearFilters",
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
            "description": "Table: clearFilters Clears all the filters currently applied on the table."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "30d1f86d-d3ed-49a6-996c-626630decf67"
            }
          ]
        },
        {
          "id": "546c24c6-b7c4-4f6f-a62a-c6da2f2f4ca6",
          "name": "Table:ClearFilters1",
          "request": {
            "url": "http://graph.microsoft.com/workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/clearFilters",
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
            "description": "Table: clearFilters Clears all the filters currently applied on the table."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9b19eb99-fb48-40d4-a918-ca74ce235293"
            }
          ]
        }
      ]
    }
  ]
}