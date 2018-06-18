---
swagger: "2.0"
x-collection-name: OneNote
x-complete: 1
info:
  title: One Note
  description: easily-capture-content-into-onenote-with-this-rest-api-
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
    parameters:
      summary: Parameters Pages Pageid Content
      description: Parameters pages pageid content.
      operationId: parametersPagesPageContent
      x-api-path-slug: pagespageidcontent-parameters
      responses:
        200:
          description: OK
      tags:
      - Pages
      - PageId
      - Content
---