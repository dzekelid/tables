---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 0
info:
  title: Xignite Currencies Get Historical Cross Rate Tables
  description: Returns historical currency cross-rate tables for a range of dates.
  version: 1.0.0
host: www.xignite.com/xCurrencies.json
basePath: /XigniteCurrencies
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /GetHistoricalCrossRateTables:
    get:
      summary: Get Historical Cross Rate Tables
      description: Returns historical currency cross-rate tables for a range of dates.
      operationId: postGethistoricalcrossratetables
      x-api-path-slug: gethistoricalcrossratetables-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Historical
      - Cross
      - Rate
      - Tables
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