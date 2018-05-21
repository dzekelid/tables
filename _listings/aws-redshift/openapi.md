---
swagger: "2.0"
x-collection-name: AWS Redshift
x-complete: 1
info:
  title: AWS Redshift API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeTableRestoreStatus:
    get:
      summary: Describe Table Restore Status
      description: Lists the status of one or more table restore requests made using
        the.
      operationId: describeTableRestoreStatus
      x-api-path-slug: actiondescribetablerestorestatus-get
      parameters:
      - in: query
        name: ClusterIdentifier
        description: The Amazon Redshift cluster that the table is being restored
          to
        type: string
      - in: query
        name: Marker
        description: An optional pagination token provided by a previous                DescribeTableRestoreStatus
          request
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of records to include in the response
        type: string
      - in: query
        name: TableRestoreRequestId
        description: The identifier of the table restore request to return status
          for
        type: string
      responses:
        200:
          description: OK
      tags:
      - Tables
---