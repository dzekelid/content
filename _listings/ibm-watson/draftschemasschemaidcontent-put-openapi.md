---
swagger: "2.0"
x-collection-name: IBM Watson
x-complete: 0
info:
  title: IBM Watson IoT Platform Update the content of a draft schema definition file
  description: |-
    Updates the content of a draft schema definition file with the specified
    id.

    The schema definition file is passed to the Watson IoT Platform within a
    multipart POST (multipart/form-data).  The body of the POST **must**
    contain one part with a name of the **schemaFile** and the
    actual schema file as the body of the part.

    Please note that the schemaFilename and contentType properties of the
    schema definition will also be updated as a result of updating the
    content of the schema file.
  version: 1.0.0
basePath: /api/v0002
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /schemas/{schemaId}/content:
    get:
      summary: Get the contents of the active schema definition file
      description: |-
        Retrieves the content of the active schema definition file with the
        specified id.
      operationId: retrieves-the-content-of-the-active-schema-definition-file-with-thespecified-id
      x-api-path-slug: schemasschemaidcontent-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Schemas
      - SchemaId
      - Content
  /draft/schemas/{schemaId}/content:
    get:
      summary: Get the contents of the draft schema definition file
      description: |-
        Retrieves the content of the draft schema definition file with the
        specified id.
      operationId: retrieves-the-content-of-the-draft-schema-definition-file-with-thespecified-id
      x-api-path-slug: draftschemasschemaidcontent-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Draft
      - Schemas
      - SchemaId
      - Content
    put:
      summary: Update the content of a draft schema definition file
      description: |-
        Updates the content of a draft schema definition file with the specified
        id.

        The schema definition file is passed to the Watson IoT Platform within a
        multipart POST (multipart/form-data).  The body of the POST **must**
        contain one part with a name of the **schemaFile** and the
        actual schema file as the body of the part.

        Please note that the schemaFilename and contentType properties of the
        schema definition will also be updated as a result of updating the
        content of the schema file.
      operationId: updates-the-content-of-a-draft-schema-definition-file-with-the-specifiedidthe-schema-definition-file
      x-api-path-slug: draftschemasschemaidcontent-put
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Draft
      - Schemas
      - SchemaId
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