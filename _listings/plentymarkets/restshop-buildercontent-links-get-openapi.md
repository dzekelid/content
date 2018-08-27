---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets List all content links for a given plugin set
  description: List all content links for a given plugin set.
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/documents/{documentId}:
    get:
      summary: Download the content of a document
      description: Downloads the content of a document. The ID of the document must
        be specified.
      operationId: getRestDocumentsDocument
      x-api-path-slug: restdocumentsdocumentid-get
      parameters:
      - in: path
        name: documentId
      responses:
        200:
          description: OK
      tags:
      - Download
      - Content
      - Of
      - Document
  /rest/shop_builder/content_links:
    get:
      summary: List all content links for a given plugin set
      description: List all content links for a given plugin set.
      operationId: getRestShopBuilderContentLinks
      x-api-path-slug: restshop-buildercontent-links-get
      responses:
        200:
          description: OK
      tags:
      - List
      - ""
      - Content
      - Linksa
      - Given
      - Plugin
      - Set
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