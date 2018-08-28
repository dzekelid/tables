---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 0
info:
  title: Xignite Currencies Get Real Time Cross Rate Table With Bid Ask
  description: Returns a real-time currency cross-rate table.
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
  /GetHistoricalCrossRateTablesBidAsk:
    get:
      summary: Get Historical Cross Rate Tables Bid Ask
      description: Returns historical currency cross-rate tables for a range of dates.
      operationId: postGethistoricalcrossratetablesbask
      x-api-path-slug: gethistoricalcrossratetablesbidask-get
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
      - Bid
      - Ask
  /GetHistoricalCrossRateTable:
    get:
      summary: Get Historical Cross Rate Table
      description: Returns a historical currency cross-rate table.
      operationId: postGethistoricalcrossratetable
      x-api-path-slug: gethistoricalcrossratetable-get
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
      - Table
  /GetHistoricalCrossRateTableBidAsk:
    get:
      summary: Get Historical Cross Rate Table Bid Ask
      description: Returns a historical currency cross-rate table.
      operationId: postGethistoricalcrossratetablebask
      x-api-path-slug: gethistoricalcrossratetablebidask-get
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
      - Table
      - Bid
      - Ask
  /GetRealTimeCrossRateTable:
    get:
      summary: Get Real Time Cross Rate Table
      description: Returns a real-time currency cross-rate table.
      operationId: postGetrealtimecrossratetable
      x-api-path-slug: getrealtimecrossratetable-get
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
      - Real
      - Time
      - Cross
      - Rate
      - Table
  /GetRealTimeCrossRateTableWithBidAsk:
    get:
      summary: Get Real Time Cross Rate Table With Bid Ask
      description: Returns a real-time currency cross-rate table.
      operationId: postGetrealtimecrossratetablewithbask
      x-api-path-slug: getrealtimecrossratetablewithbidask-get
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
      - Real
      - Time
      - Cross
      - Rate
      - Table
      - With
      - Bid
      - Ask
  /GetRealTimeCrossRateTableAsHTML:
    get:
      summary: Get Real Time Cross Rate Table As H T M L
      description: Returns a real-time currency cross-rate table as an HTML Output.
      operationId: postGetrealtimecrossratetableashtml
      x-api-path-slug: getrealtimecrossratetableashtml-get
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
      - Real
      - Time
      - Cross
      - Rate
      - Table
      - As
      - H
      - T
      - M
      - L
  /GetSimpleRealTimeCrossRateTableAsHTML:
    get:
      summary: Get Simple Real Time Cross Rate Table As H T M L
      description: Returns a real-time currency cross-rate table as an HTML Output.
      operationId: postGetsimplerealtimecrossratetableashtml
      x-api-path-slug: getsimplerealtimecrossratetableashtml-get
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
      - Simple
      - Real
      - Time
      - Cross
      - Rate
      - Table
      - As
      - H
      - T
      - M
      - L
  /GetHistoricalCrossRateTableAsHTML:
    get:
      summary: Get Historical Cross Rate Table As H T M L
      description: Returns a historical currency cross-rate table as an HTML Output.
      operationId: postGethistoricalcrossratetableashtml
      x-api-path-slug: gethistoricalcrossratetableashtml-get
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
      - Table
      - As
      - H
      - T
      - M
      - L
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