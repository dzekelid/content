---
swagger: "2.0"
x-collection-name: Box
x-complete: 1
info:
  title: Box
  description: the-box-content-api-gives-you-access-to-secure-content-management-and-content-experience-features-for-use-in-your-own-app--it-strives-to-be-restful-and-is-organized-around-the-main-resources-youre-familiar-with-from-the-box-web-interface-
  version: 1.0.0
host: api.box.com
basePath: /2.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /files/content:
    options:
      summary: File upload preflight check
      description: The Pre-flight check API will verify that a file will be accepted
        by Box before you send all the bytes over the wire.
      operationId: fileUploadPreflightCheck
      x-api-path-slug: filescontent-options
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Files
      - Content
  /files/{FILE_ID}/content:
    get:
      summary: Download File
      description: Retrieves the actual data of the file. An optional version parameter
        can be set to download a previous version of the file.
      operationId: getFileContent
      x-api-path-slug: filesfile-idcontent-get
      parameters:
      - in: header
        name: BoxApi
        description: The shared link for this item
      - in: path
        name: FILE_ID
      - in: header
        name: Range
        description: The range value in bytes
      - in: query
        name: version
        description: The ID specific version of this file to download
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Files
      - File
      - ""
      - Content
---