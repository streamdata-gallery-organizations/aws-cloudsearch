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
  /?Action=DescribeExpressions:
    get:
      summary: Describe Expressions
      description: Gets the expressions configured for the search domain
      operationId: DescribeExpressions
      parameters:
      - in: query
        name: Deployed
        description: Whether to display the deployed configuration (true) or include
          any pending changes (false)
        type: string
      - in: query
        name: DomainName
        description: The name of the domain you want to describe
        type: string
      - in: query
        name: ExpressionNames.member.N
        description: Limits the                         DescribeExpressions                      response
          to the specified expressions
        type: string
      responses:
        200:
          description: OK
      tags:
      - expressions
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