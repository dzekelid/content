---
swagger: "2.0"
x-collection-name: Sustainable Facilities Tool API
x-complete: 1
info:
  title: Sustainable Facilities Tool API
  description: our-core-api-allows-developers-to-interact-with-the-sustainable-facilities-tool-programmatically--its-designed-for-public-use-and-to-be-easily-integrated-into-other-applications-
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
---