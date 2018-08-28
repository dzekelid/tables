{
  "info": {
    "name": "AWS Database Migration Service API Describe Table Statistics",
    "_postman_id": "3385acb2-745d-4e15-8e46-5947e35aa68e",
    "description": "Returns table statistics on the database migration task, including table name, rows inserted, rows updated, and rows deleted.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Table Statistics",
      "item": [
        {
          "id": "9fb3857d-4b13-4f99-a17e-efd9bd35314a",
          "name": "describeTableStatistics",
          "request": {
            "url": "http://example.com/api/?Action=DescribeTableStatistics?Marker=Marker&MaxRecords=MaxRecords&ReplicationTaskArn=ReplicationTaskArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns table statistics on the database migration task, including table name, rows inserted, rows updated, and rows deleted."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8762dbbc-8d27-4ffb-b004-d1dd79bc67a0"
            }
          ]
        }
      ]
    }
  ]
}