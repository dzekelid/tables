---
swagger: "2.0"
x-collection-name: Google Fusion Tables
x-complete: 0
info:
  title: Google Fusion Tables API Get Tables
  description: Retrieves a list of tables a user owns.
  contact:
    name: Google
    url: https://google.com
  version: v2
host: www.googleapis.com
basePath: /fusiontables/v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /tables:
    get:
      summary: Get Tables
      description: Retrieves a list of tables a user owns.
      operationId: fusiontables.table.list
      x-api-path-slug: tables-get
      parameters:
      - in: query
        name: maxResults
        description: Maximum number of tables to return
      - in: query
        name: pageToken
        description: Continuation token specifying which result page to return
      responses:
        200:
          description: OK
      tags:
      - Table
    post:
      summary: Create Table
      description: Creates a new table.
      operationId: fusiontables.table.insert
      x-api-path-slug: tables-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Table
  /tables/import:
    post:
      summary: Import Table
      description: Imports a new table.
      operationId: fusiontables.table.importTable
      x-api-path-slug: tablesimport-post
      parameters:
      - in: query
        name: delimiter
        description: The delimiter used to separate cell values
      - in: query
        name: encoding
        description: The encoding of the content
      - in: query
        name: name
        description: The name to be assigned to the new table
      responses:
        200:
          description: OK
      tags:
      - Table
  /tables/{tableId}:
    delete:
      summary: Delete Table
      description: Deletes a table.
      operationId: fusiontables.table.delete
      x-api-path-slug: tablestableid-delete
      parameters:
      - in: path
        name: tableId
        description: ID of the table to be deleted
      responses:
        200:
          description: OK
      tags:
      - Table
    get:
      summary: Get Table
      description: Retrieves a specific table by its ID.
      operationId: fusiontables.table.get
      x-api-path-slug: tablestableid-get
      parameters:
      - in: path
        name: tableId
        description: Identifier for the table being requested
      responses:
        200:
          description: OK
      tags:
      - Table
    patch:
      summary: Update Table
      description: Updates an existing table. Unless explicitly requested, only the
        name, description, and attribution will be updated. This method supports patch
        semantics.
      operationId: fusiontables.table.patch
      x-api-path-slug: tablestableid-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: replaceViewDefinition
        description: Whether the view definition is also updated
      - in: path
        name: tableId
        description: ID of the table that is being updated
      responses:
        200:
          description: OK
      tags:
      - Table
    put:
      summary: Update Table
      description: Updates an existing table. Unless explicitly requested, only the
        name, description, and attribution will be updated.
      operationId: fusiontables.table.update
      x-api-path-slug: tablestableid-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: replaceViewDefinition
        description: Whether the view definition is also updated
      - in: path
        name: tableId
        description: ID of the table that is being updated
      responses:
        200:
          description: OK
      tags:
      - Table
  /tables/{tableId}/copy:
    post:
      summary: Copy Table
      description: Copies a table.
      operationId: fusiontables.table.copy
      x-api-path-slug: tablestableidcopy-post
      parameters:
      - in: query
        name: copyPresentation
        description: Whether to also copy tabs, styles, and templates
      - in: path
        name: tableId
        description: ID of the table that is being copied
      responses:
        200:
          description: OK
      tags:
      - Table
  /tables/{tableId}/import:
    post:
      summary: import Rows
      description: Imports more rows into a table.
      operationId: fusiontables.table.importRows
      x-api-path-slug: tablestableidimport-post
      parameters:
      - in: query
        name: delimiter
        description: The delimiter used to separate cell values
      - in: query
        name: encoding
        description: The encoding of the content
      - in: query
        name: endLine
        description: The index of the line up to which data will be imported
      - in: query
        name: isStrict
        description: Whether the imported CSV must have the same number of values
          for each row
      - in: query
        name: startLine
        description: The index of the first line from which to start importing, inclusive
      - in: path
        name: tableId
        description: The table into which new rows are being imported
      responses:
        200:
          description: OK
      tags:
      - Table
  /tables/{tableId}/replace:
    post:
      summary: Replace Rows
      description: Replaces rows of an existing table. Current rows remain visible
        until all replacement rows are ready.
      operationId: fusiontables.table.replaceRows
      x-api-path-slug: tablestableidreplace-post
      parameters:
      - in: query
        name: delimiter
        description: The delimiter used to separate cell values
      - in: query
        name: encoding
        description: The encoding of the content
      - in: query
        name: endLine
        description: The index of the line up to which data will be imported
      - in: query
        name: isStrict
        description: Whether the imported CSV must have the same number of column
          values for each row
      - in: query
        name: startLine
        description: The index of the first line from which to start importing, inclusive
      - in: path
        name: tableId
        description: Table whose rows will be replaced
      responses:
        200:
          description: OK
      tags:
      - Table
  /tables/{tableId}/styles:
    get:
      summary: Get Styels
      description: Retrieves a list of styles.
      operationId: fusiontables.style.list
      x-api-path-slug: tablestableidstyles-get
      parameters:
      - in: query
        name: maxResults
        description: Maximum number of styles to return
      - in: query
        name: pageToken
        description: Continuation token specifying which result page to return
      - in: path
        name: tableId
        description: Table whose styles are being listed
      responses:
        200:
          description: OK
      tags:
      - Table Style
    post:
      summary: Create Style
      description: Adds a new style for the table.
      operationId: fusiontables.style.insert
      x-api-path-slug: tablestableidstyles-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: tableId
        description: Table for which a new style is being added
      responses:
        200:
          description: OK
      tags:
      - Table Style
  /tables/{tableId}/styles/{styleId}:
    delete:
      summary: Delete Style
      description: Deletes a style.
      operationId: fusiontables.style.delete
      x-api-path-slug: tablestableidstylesstyleid-delete
      parameters:
      - in: path
        name: styleId
        description: Identifier (within a table) for the style being deleted
      - in: path
        name: tableId
        description: Table from which the style is being deleted
      responses:
        200:
          description: OK
      tags:
      - Table Style
    get:
      summary: DelGetete Style
      description: Gets a specific style.
      operationId: fusiontables.style.get
      x-api-path-slug: tablestableidstylesstyleid-get
      parameters:
      - in: path
        name: styleId
        description: Identifier (integer) for a specific style in a table
      - in: path
        name: tableId
        description: Table to which the requested style belongs
      responses:
        200:
          description: OK
      tags:
      - Table Style
    patch:
      summary: Update Style
      description: Updates an existing style. This method supports patch semantics.
      operationId: fusiontables.style.patch
      x-api-path-slug: tablestableidstylesstyleid-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: styleId
        description: Identifier (within a table) for the style being updated
      - in: path
        name: tableId
        description: Table whose style is being updated
      responses:
        200:
          description: OK
      tags:
      - Table Style
    put:
      summary: Update Style
      description: Updates an existing style.
      operationId: fusiontables.style.update
      x-api-path-slug: tablestableidstylesstyleid-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: styleId
        description: Identifier (within a table) for the style being updated
      - in: path
        name: tableId
        description: Table whose style is being updated
      responses:
        200:
          description: OK
      tags:
      - Table Style
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