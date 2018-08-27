---
swagger: "2.0"
x-collection-name: Entertainment Express
x-complete: 0
info:
  title: Entertainment Express Paged list of companies.
  description: 'Companies are listed in a movie, show, or game response as those whom
    are involved with the program.  EX: Universal Pictures.'
  version: "2.0"
host: ee.iva-api.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Common/Companies/:
    get:
      summary: Paged list of companies.
      description: 'Companies are listed in a movie, show, or game response as those
        whom are involved with the program.  EX: Universal Pictures.'
      operationId: GetCompanies
      x-api-path-slug: commoncompanies-get
      parameters:
      - in: query
        name: Skip
        description: Offset for paging
      - in: query
        name: Take
        description: Maximum number of rows returned
      responses:
        200:
          description: OK
      tags:
      - Common
      - Companies
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