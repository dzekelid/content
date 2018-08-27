swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 1
info:
  title: plentymarkets REST-API
  description: the-plentymarkets-rest-api-expands-the-functionality-of-the-plentymarkets-cms-and-allows-access-to-resources-i-e--data-records-via-unique-uri-paths
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
  /rest/shop_builder/contents/{contentId}:
    delete:
      summary: Delete a content
      description: Delete a content.
      operationId: deleteRestShopBuilderContentsContent
      x-api-path-slug: restshop-buildercontentscontentid-delete
      parameters:
      - in: path
        name: contentId
      responses:
        200:
          description: OK
      tags:
      - Content
    get:
      summary: Find a content by id.
      description: Find a content by id..
      operationId: getRestShopBuilderContentsContent
      x-api-path-slug: restshop-buildercontentscontentid-get
      parameters:
      - in: path
        name: contentId
      responses:
        200:
          description: OK
      tags:
      - Find
      - Content
      - By
      - Id
    put:
      summary: Update a content.
      description: Update a content..
      operationId: putRestShopBuilderContentsContent
      x-api-path-slug: restshop-buildercontentscontentid-put
      parameters:
      - in: body
        name: /rest/shop_builder/contents/{contentId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: contentId
      responses:
        200:
          description: OK
      tags:
      - Content
  /rest/shop_builder/pages:
    get:
      summary: List content pages from all plugins in a given plugin set.
      description: List content pages from all plugins in a given plugin set..
      operationId: getRestShopBuilderPages
      x-api-path-slug: restshop-builderpages-get
      responses:
        200:
          description: OK
      tags:
      - List
      - Content
      - Pages
      - From
      - ""
      - Plugins
      - In
      - Given
      - Plugin
      - Set
  /rest/storage/plugins/inbox/object-url:
    get:
      summary: Get the content of a file from the inbox
      description: Gets the content of a file stored in the inbox. The storage key
        (i.e. file path) must be specified.
      operationId: getRestStoragePluginsInboxObjectUrl
      x-api-path-slug: reststoragepluginsinboxobjecturl-get
      parameters:
      - in: query
        name: key
        description: The storage key for the file to retrieve
      responses:
        200:
          description: OK
      tags:
      - Content
      - Of
      - File
      - From
      - Inbox