---
swagger: "2.0"
x-collection-name: Firebase
x-complete: 0
info:
  title: Firebase Rules Parameters Name Getexecutable
  description: Parameters name getexecutable.
  contact:
    name: Google
    url: https://google.com
  version: 1.0.0
host: firebaserules.googleapis.com
basePath: v1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{name}:getExecutable:
    get:
      summary: Get Name Getexecutable
      description: Get the `Release` executable to use when enforcing rules.
      operationId: getNameGetexecutable
      x-api-path-slug: namegetexecutable-get
      parameters:
      - in: query
        name: executableVersion
        description: The requested runtime executable version
      - in: path
        name: name
        description: Resource name of the `Release`
      responses:
        200:
          description: OK
      tags:
      - Names
      - Executables
    parameters:
      summary: Parameters Name Getexecutable
      description: Parameters name getexecutable.
      operationId: parametersNameGetexecutable
      x-api-path-slug: namegetexecutable-parameters
      responses:
        200:
          description: OK
      tags:
      - Names
      - Executables
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