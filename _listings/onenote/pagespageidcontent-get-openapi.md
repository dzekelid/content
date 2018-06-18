---
swagger: "2.0"
x-collection-name: OneNote
x-complete: 0
info:
  title: One Note Get Pages Pageid Content
  description: Returns HTML content of the specified page.
  version: 1.0.0
host: www.onenote.com
basePath: /api/v1.0/me/notes/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /pages/{pageId}/content:
    get:
      summary: Get Pages Pageid Content
      description: Returns HTML content of the specified page.
      operationId: getPagesPageContent
      x-api-path-slug: pagespageidcontent-get
      parameters:
      - in: header
        name: Accept
        description: 'Required: indicates type of content returned in the response'
      - in: query
        name: Accept
        description: 'Required: indicates type of content returned in the response'
      - in: query
        name: includeIDs
        description: 'Optional: set to true to get generated IDs to use for PATCH
          operations'
      - in: path
        name: pageId
        description: Specifies the page whose content you want to retrieve
      responses:
        200:
          description: OK
      tags:
      - Pages
      - PageId
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