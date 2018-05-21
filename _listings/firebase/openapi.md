---
swagger: "2.0"
x-collection-name: Firebase
x-complete: 1
info:
  title: Firebase Rules
  description: creates-and-manages-rules-that-determine-when-a-firebase-rulesenabled-service-should-permit-a-request
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
---