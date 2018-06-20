---
swagger: "2.0"
x-collection-name: GlobalChange.gov
x-complete: 1
info:
  title: Global Change Information System API
  description: who-we-are-what-the-gcis-is-and-how-we-use-identifiers-and-semantic-information-to-provide-points-of-reference-and-traceability--examples-and-tutorials-for-using-this-system-as-a-researcher-citizen-scientist-application-developer-or-information-theorist--a-description-of-how-the-information-is-structured-including-the-overlaps-between-relational-and-semantic-representations-of-the-information--complete-documentation-for-the-api-including-methods-for-browsing-and-finding-resources-
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
---