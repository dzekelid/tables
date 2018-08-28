{
  "info": {
    "name": "Dezrez Update SystemStatus of ScheduledTask to Active, Inactive, Deleted or Archived.",
    "_postman_id": "4151db02-7bcf-4fc9-999b-e203bdad4a45",
    "description": "Update systemstatus of scheduledtask to active, inactive, deleted or archived..",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "SystemStatus",
      "item": [
        {
          "id": "bb6c0190-e931-481e-a36e-72837cd15882",
          "name": "Branch_UpdateScheduledTaskStatusByidBysystemStatus",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.dezrez.com",
              "path": [
                "api/branch/updatescheduledtaskstatus/:id"
              ],
              "query": [
                {
                  "key": "systemStatus",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "header": [
              {
                "key": "Rezi-Api-Version",
                "value": "{}",
                "description": "Specifies which version of the API to call",
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
            "description": "Update systemstatus of scheduledtask to active, inactive, deleted or archived.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5891bd92-27d4-456a-aa0d-80e521edee77"
            }
          ]
        }
      ]
    }
  ]
}