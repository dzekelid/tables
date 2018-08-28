---
swagger: "2.0"
x-collection-name: GlobalChange.gov
x-complete: 0
info:
  title: Global Change Information System API Get a representation of a table.
  description: Get JSON which represents the structure of a table.
  version: v1
host: data.globalchange.gov
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /report/{report_identifier}/chapter/{chapter_identifier}/table:
    get:
      summary: List tables in a chapter
      description: Get a list of tables in a chapter.
      operationId: get-a-list-of-tables-in-a-chapter
      x-api-path-slug: reportreport-identifierchapterchapter-identifiertable-get
      parameters:
      - in: query
        name: all
        description: Set to 1 to get all of the tables
      - in: path
        name: chapter_identifier
        description: chapter_identifier description
      - in: query
        name: page
        description: The page number (starting at 1)
      - in: path
        name: report_identifier
        description: report_identifier description
      responses:
        200:
          description: OK
      tags:
      - Tables
      - Chapter
  /report/{report_identifier}/table:
    get:
      summary: List tables in a report.
      description: List the tables in a report, 20 per page.
      operationId: list-the-tables-in-a-report-20-per-page
      x-api-path-slug: reportreport-identifiertable-get
      parameters:
      - in: query
        name: all
        description: Set to 1 to get all of the tables
      - in: query
        name: page
        description: The page number (starting at 1)
      - in: path
        name: report_identifier
        description: report_identifier description
      responses:
        200:
          description: OK
      tags:
      - Tables
      - Report
  /report/{report_identifier}/chapter/{chapter_identifier}/table/{table_identifier}:
    get:
      summary: Get a representation of a table in a chapter.
      description: Get JSON which represents the structure of a table in a chapter.
      operationId: get-json-which-represents-the-structure-of-a-table-in-a-chapter
      x-api-path-slug: reportreport-identifierchapterchapter-identifiertabletable-identifier-get
      parameters:
      - in: path
        name: chapter_identifier
        description: chapter_identifier description
      - in: path
        name: report_identifier
        description: report_identifier description
      - in: path
        name: table_identifier
        description: table_identifier description
      - in: query
        name: with_gcmd
        description: Include GCMD keywords associated with the table
      - in: query
        name: with_regions
        description: Include regions associated with the table
      responses:
        200:
          description: OK
      tags:
      - Representation
      - Table
      - Chapter
  /report/{report_identifier}/table/{table_identifier}:
    get:
      summary: Get a representation of a table.
      description: Get JSON which represents the structure of a table.
      operationId: get-json-which-represents-the-structure-of-a-table
      x-api-path-slug: reportreport-identifiertabletable-identifier-get
      parameters:
      - in: path
        name: report_identifier
        description: report_identifier description
      - in: path
        name: table_identifier
        description: table_identifier description
      - in: query
        name: with_gcmd
        description: Include GCMD keywords associated with the table
      - in: query
        name: with_regions
        description: Include regions associated with the table
      responses:
        200:
          description: OK
      tags:
      - Representation
      - Table
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