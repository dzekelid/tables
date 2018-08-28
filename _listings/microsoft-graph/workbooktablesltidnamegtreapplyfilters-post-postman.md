{
  "info": {
    "name": "Microsoft Graph API Table Reapply Filters",
    "_postman_id": "f1cb0ed0-1d9f-4855-a81f-55143bd3ed72",
    "description": "Table: reapplyFilters Reapplies all the filters currently on the table.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Table",
      "item": [
        {
          "id": "977debd1-9f90-4ed3-a07c-3021a493b17c",
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
              "id": "0a53f3f8-b2cc-4717-8bc3-c4c433f0a864"
            }
          ]
        },
        {
          "id": "7ea46a1d-f71a-4f99-bf99-5c42ba78d3e6",
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
              "id": "25eed002-4d1f-4ea2-92fa-4cbfbe4ff84c"
            }
          ]
        },
        {
          "id": "87d13ca5-0db8-40c1-8ce0-9ced10188c00",
          "name": "Table:ReapplyFilters",
          "request": {
            "url": "http://graph.microsoft.com/workbook/tables(&lt;id|name&gt;)/reapplyFilters",
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
            "description": "Table: reapplyFilters Reapplies all the filters currently on the table."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "da30472d-bf44-4b3e-9118-f79264f209d4"
            }
          ]
        }
      ]
    }
  ]
}