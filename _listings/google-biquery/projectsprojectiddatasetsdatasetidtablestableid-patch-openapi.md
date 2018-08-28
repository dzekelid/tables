---
swagger: "2.0"
x-collection-name: Google Biquery
x-complete: 0
info:
  title: Google BigQuery API Update Table
  description: Updates information in an existing table. The update method replaces
    the entire table resource, whereas the patch method only replaces fields that
    are provided in the submitted table resource. This method supports patch semantics.
  contact:
    name: Google
    url: https://google.com
  version: v2
host: www.googleapis.com
basePath: /bigquery/v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /projects/{projectId}/datasets/{datasetId}/tables:
    get:
      summary: Get Tables
      description: Lists all tables in the specified dataset. Requires the READER
        dataset role.
      operationId: bigquery.tables.list
      x-api-path-slug: projectsprojectiddatasetsdatasetidtables-get
      parameters:
      - in: path
        name: datasetId
        description: Dataset ID of the tables to list
      - in: query
        name: maxResults
        description: Maximum number of results to return
      - in: query
        name: pageToken
        description: Page token, returned by a previous call, to request the next
          page of results
      - in: path
        name: projectId
        description: Project ID of the tables to list
      responses:
        200:
          description: OK
      tags:
      - Table
    post:
      summary: Create Table
      description: Creates a new, empty table in the dataset.
      operationId: bigquery.tables.insert
      x-api-path-slug: projectsprojectiddatasetsdatasetidtables-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: datasetId
        description: Dataset ID of the new table
      - in: path
        name: projectId
        description: Project ID of the new table
      responses:
        200:
          description: OK
      tags:
      - Table
  /projects/{projectId}/datasets/{datasetId}/tables/{tableId}:
    delete:
      summary: Delete Table
      description: Deletes the table specified by tableId from the dataset. If the
        table contains data, all the data will be deleted.
      operationId: bigquery.tables.delete
      x-api-path-slug: projectsprojectiddatasetsdatasetidtablestableid-delete
      parameters:
      - in: path
        name: datasetId
        description: Dataset ID of the table to delete
      - in: path
        name: projectId
        description: Project ID of the table to delete
      - in: path
        name: tableId
        description: Table ID of the table to delete
      responses:
        200:
          description: OK
      tags:
      - Table
    get:
      summary: Get Tble
      description: Gets the specified table resource by table ID. This method does
        not return the data in the table, it only returns the table resource, which
        describes the structure of this table.
      operationId: bigquery.tables.get
      x-api-path-slug: projectsprojectiddatasetsdatasetidtablestableid-get
      parameters:
      - in: path
        name: datasetId
        description: Dataset ID of the requested table
      - in: path
        name: projectId
        description: Project ID of the requested table
      - in: path
        name: tableId
        description: Table ID of the requested table
      responses:
        200:
          description: OK
      tags:
      - Table
    patch:
      summary: Update Table
      description: Updates information in an existing table. The update method replaces
        the entire table resource, whereas the patch method only replaces fields that
        are provided in the submitted table resource. This method supports patch semantics.
      operationId: bigquery.tables.patch
      x-api-path-slug: projectsprojectiddatasetsdatasetidtablestableid-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: datasetId
        description: Dataset ID of the table to update
      - in: path
        name: projectId
        description: Project ID of the table to update
      - in: path
        name: tableId
        description: Table ID of the table to update
      responses:
        200:
          description: OK
      tags:
      - Table
    put:
      summary: Update Table
      description: Updates information in an existing table. The update method replaces
        the entire table resource, whereas the patch method only replaces fields that
        are provided in the submitted table resource.
      operationId: bigquery.tables.update
      x-api-path-slug: projectsprojectiddatasetsdatasetidtablestableid-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: datasetId
        description: Dataset ID of the table to update
      - in: path
        name: projectId
        description: Project ID of the table to update
      - in: path
        name: tableId
        description: Table ID of the table to update
      responses:
        200:
          description: OK
      tags:
      - Table
  /projects/{projectId}/datasets/{datasetId}/tables/{tableId}/data:
    get:
      summary: Get Table
      description: Retrieves table data from a specified set of rows. Requires the
        READER dataset role.
      operationId: bigquery.tabledata.list
      x-api-path-slug: projectsprojectiddatasetsdatasetidtablestableiddata-get
      parameters:
      - in: path
        name: datasetId
        description: Dataset ID of the table to read
      - in: query
        name: maxResults
        description: Maximum number of results to return
      - in: query
        name: pageToken
        description: Page token, returned by a previous call, identifying the result
          set
      - in: path
        name: projectId
        description: Project ID of the table to read
      - in: query
        name: startIndex
        description: Zero-based index of the starting row to read
      - in: path
        name: tableId
        description: Table ID of the table to read
      responses:
        200:
          description: OK
      tags:
      - Table Data
  /projects/{projectId}/datasets/{datasetId}/tables/{tableId}/insertAll:
    post:
      summary: Insert Data
      description: Streams data into BigQuery one record at a time without needing
        to run a load job. Requires the WRITER dataset role.
      operationId: bigquery.tabledata.insertAll
      x-api-path-slug: projectsprojectiddatasetsdatasetidtablestableidinsertall-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: datasetId
        description: Dataset ID of the destination table
      - in: path
        name: projectId
        description: Project ID of the destination table
      - in: path
        name: tableId
        description: Table ID of the destination table
      responses:
        200:
          description: OK
      tags:
      - Table Data
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