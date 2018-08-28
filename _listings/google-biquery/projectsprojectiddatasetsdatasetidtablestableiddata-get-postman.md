{
  "info": {
    "name": "Google BigQuery API Get Table",
    "_postman_id": "e24b7f7a-4d1b-46cd-89c7-673eace04a8d",
    "description": "Retrieves table data from a specified set of rows. Requires the READER dataset role.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "table data",
      "item": [
        {
          "id": "ac26cdfe-3447-422a-bfb7-be3dea4a26bc",
          "name": "bigquery.tabledata.list",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.googleapis.com",
              "path": [
                "bigquery",
                "v2",
                "projects/:projectId/datasets/:datasetId/tables/:tableId/data"
              ],
              "query": [
                {
                  "key": "maxResults",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "pageToken",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "startIndex",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "datasetId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "projectId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "tableId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves table data from a specified set of rows"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f00d1b87-8f01-4bc8-bfe1-bbdec74cb5f1"
            }
          ]
        }
      ]
    }
  ]
}