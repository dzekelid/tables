swagger: "2.0"
x-collection-name: AWS Database Migration Service
x-complete: 1
info:
  title: AWS Database Migration Service API
  version: 1.0.0
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