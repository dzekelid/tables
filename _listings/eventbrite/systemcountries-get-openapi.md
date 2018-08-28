---
swagger: "2.0"
x-collection-name: Eventbrite
x-complete: 0
info:
  title: Eventbrite Get System Countries
  description: |-
    Returns a single page response with a key of countries,
    containing a list of countries.
  version: 1.0.0
host: www.eventbrite.com
basePath: /%7Bdata-type%7D/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /system/timezones/:
    get:
      summary: Get System Timezones
      description: |-
        Returns a paginated response with a key of timezones,
        containing a list of timezones.
      operationId: getSystemTimezones
      x-api-path-slug: systemtimezones-get
      responses:
        200:
          description: OK
      tags:
      - System
      - Timezones
  /system/regions/:
    get:
      summary: Get System Regions
      description: |-
        Returns a single page response with a key of regions,
        containing a list of regions.
      operationId: getSystemRegions
      x-api-path-slug: systemregions-get
      responses:
        200:
          description: OK
      tags:
      - System
      - Regions
  /system/countries/:
    get:
      summary: Get System Countries
      description: |-
        Returns a single page response with a key of countries,
        containing a list of countries.
      operationId: getSystemCountries
      x-api-path-slug: systemcountries-get
      responses:
        200:
          description: OK
      tags:
      - System
      - Countries
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