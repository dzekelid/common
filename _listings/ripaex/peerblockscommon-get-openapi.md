---
swagger: "2.0"
x-collection-name: RipaEx
x-complete: 0
info:
  title: RipaEx Peer Blocks Common
  description: Get a list of blocks by ids.
  version: 1.0.0
host: api.ripaex.io
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /peer/blocks/common:
    get:
      summary: Peer Blocks Common
      description: Get a list of blocks by ids.
      operationId: transport.commonBlock
      x-api-path-slug: peerblockscommon-get
      parameters:
      - in: query
        name: ids
        description: A list of block IDs
      responses:
        200:
          description: OK
      tags:
      - Blockchain
      - Peer
      - Blocks
      - Common
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