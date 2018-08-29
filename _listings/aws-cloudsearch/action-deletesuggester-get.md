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
  /?Action=DeleteSuggester:
    get:
      summary: Delete Suggester
      description: Deletes a suggester
      operationId: DeleteSuggester
      parameters:
      - in: query
        name: DomainName
        description: A string that represents the name of a domain
        type: string
      - in: query
        name: SuggesterName
        description: Specifies the name of the suggester you want to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - suggesters
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