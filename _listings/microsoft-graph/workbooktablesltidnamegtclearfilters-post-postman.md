{
  "info": {
    "name": "Microsoft Graph API Table Clear Filters",
    "_postman_id": "4746a2b6-0c35-42e7-87e8-02a72c0520cb",
    "description": "Table: clearFilters Clears all the filters currently applied on the table.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Table",
      "item": [
        {
          "id": "adf44599-7561-4150-a37e-aaddb46d7e99",
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
              "id": "ad3d719a-33c9-4d03-8093-caae7c9267e7"
            }
          ]
        }
      ]
    }
  ]
}