---
swagger: "2.0"
x-collection-name: Entertainment Express
x-complete: 0
info:
  title: Entertainment Express Gets all VideoTypes.
  description: Returns a list of the types of videos that can be associated to a title.
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
  /Common/Countries/:
    get:
      summary: Returns a list of countries.
      description: List of Countries, ISO codes and Country IDs used throughout the
        API.
      operationId: GetCountries
      x-api-path-slug: commoncountries-get
      responses:
        200:
          description: OK
      tags:
      - Common
      - Countries
  /Common/ImageTypes/:
    get:
      summary: List of image types contained in the database.
      description: 'A list of image types available in the IVA database. **EX: Poster**'
      operationId: GetImageTypes
      x-api-path-slug: commonimagetypes-get
      responses:
        200:
          description: OK
      tags:
      - Common
      - ImageTypes
  /Common/Languages/:
    get:
      summary: Gets all languages.
      description: Returns a list of languages used in the API as well as the ISO
        code and language ID.
      operationId: GetLanguages
      x-api-path-slug: commonlanguages-get
      responses:
        200:
          description: OK
      tags:
      - Common
      - Languages
  /Common/Tags/:
    get:
      summary: Gets all tags.
      description: Paged list of all tags used in the API.
      operationId: GetTags
      x-api-path-slug: commontags-get
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
      - Tags
  /Common/VideoTypes/:
    get:
      summary: Gets all VideoTypes.
      description: Returns a list of the types of videos that can be associated to
        a title.
      operationId: GetVideoTypes
      x-api-path-slug: commonvideotypes-get
      responses:
        200:
          description: OK
      tags:
      - Common
      - VideoTypes
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