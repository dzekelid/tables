---
swagger: "2.0"
x-collection-name: AWS DynamoDB
x-complete: 1
info:
  title: AWS DynamoDB API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateTable:
    get:
      summary: Create Table
      description: The CreateTable operation adds a new table to your account.
      operationId: createTable
      x-api-path-slug: actioncreatetable-get
      parameters:
      - in: query
        name: AttributeDefinitions
        description: An array of attributes that describe the key schema for the table
          and indexes
        type: string
      - in: query
        name: GlobalSecondaryIndexes
        description: One or more global secondary indexes (the maximum is five) to
          be created on the table
        type: string
      - in: query
        name: KeySchema
        description: Specifies the attributes that make up the primary key for a table
          or an index
        type: string
      - in: query
        name: LocalSecondaryIndexes
        description: One or more local secondary indexes (the maximum is five) to
          be created on the table
        type: string
      - in: query
        name: ProvisionedThroughput
        description: Represents the provisioned throughput settings for a specified
          table or index
        type: string
      - in: query
        name: StreamSpecification
        description: The settings for DynamoDB Streams on the table
        type: string
      - in: query
        name: TableName
        description: The name of the table to create
        type: string
      responses:
        200:
          description: OK
      tags:
      - Tables
  /?Action=DeleteTable:
    get:
      summary: Delete Table
      description: The DeleteTable operation deletes a table and all of its items.
      operationId: deleteTable
      x-api-path-slug: actiondeletetable-get
      parameters:
      - in: query
        name: TableName
        description: The name of the table to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Tables
  /?Action=DescribeTable:
    get:
      summary: Describe Table
      description: Returns information about the table, including the current status
        of the table, when it was created, the primary key schema, and any indexes
        on the table.
      operationId: describeTable
      x-api-path-slug: actiondescribetable-get
      parameters:
      - in: query
        name: TableName
        description: The name of the table to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Tables
  /?Action=ListTables:
    get:
      summary: List Tables
      description: Returns an array of table names associated with the current account
        and endpoint.
      operationId: listTables
      x-api-path-slug: actionlisttables-get
      parameters:
      - in: query
        name: ExclusiveStartTableName
        description: The first table name that this operation will evaluate
        type: string
      - in: query
        name: Limit
        description: A maximum number of table names to return
        type: string
      responses:
        200:
          description: OK
      tags:
      - Tables
  /?Action=UpdateTable:
    get:
      summary: Update Table
      description: Modifies the provisioned throughput settings, global secondary
        indexes, or DynamoDB Streams settings for a given table.
      operationId: updateTable
      x-api-path-slug: actionupdatetable-get
      parameters:
      - in: query
        name: AttributeDefinitions
        description: An array of attributes that describe the key schema for the table
          and indexes
        type: string
      - in: query
        name: GlobalSecondaryIndexUpdates
        description: An array of one or more global secondary indexes for the table
        type: string
      - in: query
        name: ProvisionedThroughput
        description: The new provisioned throughput settings for the specified table
          or index
        type: string
      - in: query
        name: StreamSpecification
        description: Represents the DynamoDB Streams configuration for the table
        type: string
      - in: query
        name: TableName
        description: The name of the table to be updated
        type: string
      responses:
        200:
          description: OK
      tags:
      - Tables
---