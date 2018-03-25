---
swagger: "2.0"
info:
  title: AWS CloudSearch
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=RemoveTags:
    get:
      summary: Remove Tags
      description: |-
        Removes the specified resource tags
         from an Amazon ES domain
      operationId: RemoveTags
      parameters:
      - in: query
        name: Base
        description: An error occurred while                  processing the request
        type: string
      - in: query
        name: InternalException
        description: The                  processing of the request failed because
          of an internal service error
        type: string
      - in: query
        name: ValidationException
        description: The                  request contains invalid input or is missing
          required input
        type: string
      responses:
        200:
          description: OK
      tags:
      - tags
definitions: []
x-collection-name: AWS CloudSearch
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