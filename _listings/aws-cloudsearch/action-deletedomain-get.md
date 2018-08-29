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
  /?Action=DeleteDomain:
    get:
      summary: Delete Domain
      description: Permanently deletes a search domain and all of its data
      operationId: DeleteDomain
      parameters:
      - in: query
        name: DomainName
        description: The name of the domain you want to permanently delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - domains
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