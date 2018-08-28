{
  "info": {
    "name": "Microsoft Graph API Table Reapply Filters",
    "_postman_id": "4b88f958-8187-49b6-9464-2af17b4049be",
    "description": "Table: reapplyFilters Reapplies all the filters currently on the table.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Table",
      "item": [
        {
          "id": "4cad77da-a9cc-440c-8f61-20e039d0a508",
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
              "id": "279799d9-1efe-45ca-b724-473e69f402a1"
            }
          ]
        },
        {
          "id": "ca081275-7d13-4bf7-8c07-8ef491b0e894",
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
              "id": "cd8e0e14-477c-408c-9bbc-f2f84399d574"
            }
          ]
        },
        {
          "id": "95f105f6-7d51-4d85-9334-25526a7dfa32",
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
              "id": "fc4cd92a-2172-4e99-8b60-8ef7f02fe01a"
            }
          ]
        },
        {
          "id": "4b4bff9b-bf81-4ff9-87c1-b8a8e189a924",
          "name": "Table:ReapplyFilters1",
          "request": {
            "url": "http://graph.microsoft.com/workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/reapplyFilters",
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
              "id": "4292d284-f5e9-42bb-a625-0db7d9d5b24d"
            }
          ]
        }
      ]
    }
  ]
}