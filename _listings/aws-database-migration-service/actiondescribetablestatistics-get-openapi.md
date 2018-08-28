---
swagger: "2.0"
x-collection-name: AWS Database Migration Service
x-complete: 0
info:
  title: AWS Database Migration Service API Describe Table Statistics
  version: 1.0.0
  description: Returns table statistics on the database migration task, including
    table name, rows inserted, rows updated, and rows deleted.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeTableStatistics:
    get:
      summary: Describe Table Statistics
      description: Returns table statistics on the database migration task, including
        table name, rows inserted, rows updated, and rows deleted.
      operationId: describeTableStatistics
      x-api-path-slug: actiondescribetablestatistics-get
      parameters:
      - in: query
        name: Marker
        description: An optional pagination token provided by a previous      request
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of records to include in the response
        type: string
      - in: query
        name: ReplicationTaskArn
        description: The Amazon Resource Name (ARN) of the replication task
        type: string
      responses:
        200:
          description: OK
      tags:
      - Table Statistics
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---