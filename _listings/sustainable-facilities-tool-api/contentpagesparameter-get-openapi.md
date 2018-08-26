---
swagger: "2.0"
x-collection-name: Sustainable Facilities Tool API
x-complete: 0
info:
  title: Sustainable Facilities Tool API Content Page
  description: Returns a content page by parameter.
  termsOfService: https://sftool.gov/developer/terms-of-use
  version: 1.0.0
host: api.data.gov
basePath: /sftool/v1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /contentpages:
    get:
      summary: Content Pages
      description: Returns all content pages
      operationId: returnContentPages
      x-api-path-slug: contentpages-get
      responses:
        200:
          description: OK
      tags:
      - Content
  /contentpages/{parameter}:
    get:
      summary: Content Page
      description: Returns a content page by parameter.
      operationId: returnContentPage
      x-api-path-slug: contentpagesparameter-get
      responses:
        200:
          description: OK
      tags:
      - Content
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