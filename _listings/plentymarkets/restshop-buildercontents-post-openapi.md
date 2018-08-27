---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets Create a new content.
  description: Create a new content..
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
    post:
      summary: Link a content to a a layout container of a frontend plugin.
      description: Link a content to a a layout container of a frontend plugin..
      operationId: postRestShopBuilderContentLinks
      x-api-path-slug: restshop-buildercontent-links-post
      parameters:
      - in: body
        name: /rest/shop_builder/content_links
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Link
      - Content
      - To
      - A
      - Layout
      - Container
      - Of
      - Frontend
      - Plugin
  /rest/shop_builder/content_links/{contentLinkId}:
    delete:
      summary: Delete a content link.
      description: Delete a content link..
      operationId: deleteRestShopBuilderContentLinksContentlink
      x-api-path-slug: restshop-buildercontent-linkscontentlinkid-delete
      parameters:
      - in: path
        name: contentLinkId
      responses:
        200:
          description: OK
      tags:
      - Content
      - Link
    get:
      summary: Find a content link by id.
      description: Find a content link by id..
      operationId: getRestShopBuilderContentLinksContentlink
      x-api-path-slug: restshop-buildercontent-linkscontentlinkid-get
      parameters:
      - in: path
        name: contentLinkId
      responses:
        200:
          description: OK
      tags:
      - Find
      - Content
      - Link
      - By
      - Id
    put:
      summary: Update a content link.
      description: Update a content link..
      operationId: putRestShopBuilderContentLinksContentlink
      x-api-path-slug: restshop-buildercontent-linkscontentlinkid-put
      parameters:
      - in: body
        name: /rest/shop_builder/content_links/{contentLinkId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: contentLinkId
      responses:
        200:
          description: OK
      tags:
      - Content
      - Link
  /rest/shop_builder/contents:
    post:
      summary: Create a new content.
      description: Create a new content..
      operationId: postRestShopBuilderContents
      x-api-path-slug: restshop-buildercontents-post
      parameters:
      - in: body
        name: /rest/shop_builder/contents
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - New
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