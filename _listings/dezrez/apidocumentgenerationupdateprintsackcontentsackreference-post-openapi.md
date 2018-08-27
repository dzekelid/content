---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez updates the content of a sack
  version: 1.0.0
  description: Updates the content of a sack.
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/documentgeneration/lettertemplate/properties/{id}:
    post:
      summary: Update the properties of a template, but not its content.
      description: Update the properties of a template, but not its content..
      operationId: DocumentGeneration_UpdateLetterTemplatePropertiesByidBytemplatePropertiesSaveDataContract
      x-api-path-slug: apidocumentgenerationlettertemplatepropertiesid-post
      parameters:
      - in: path
        name: id
        description: Document Id for the template
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: body
        name: templatePropertiesSaveDataContract
        description: The letter template property changes
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Properties
      - Of
      - Template
      - ""
      - But
      - Not
      - Its
      - Content
  /api/documentgeneration/deletesackcontent/{sackReference}/{envelopereference}:
    get:
      summary: "deletes an envelope from the the content of a sack \r\nDeprecated
        in favour of the DELETE verb"
      description: "Deletes an envelope from the the content of a sack \r\ndeprecated
        in favour of the delete verb."
      operationId: DocumentGeneration_DeleteSackContentDeprecatedBysackReferenceByenvelopereference
      x-api-path-slug: apidocumentgenerationdeletesackcontentsackreferenceenvelopereference-get
      parameters:
      - in: path
        name: envelopereference
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: sackReference
      responses:
        200:
          description: OK
      tags:
      - Deletes
      - Envelope
      - From
      - The
      - Content
      - Of
      - Sack
      - Deprecated
      - In
      - Favour
      - Of
      - DELETE
      - Verb
  /api/documentgeneration/sackcontent/{sackReference}/{envelopereference}:
    delete:
      summary: deletes an envelope from the the content of a sack
      description: Deletes an envelope from the the content of a sack.
      operationId: DocumentGeneration_DeleteSackContentBysackReferenceByenvelopereference
      x-api-path-slug: apidocumentgenerationsackcontentsackreferenceenvelopereference-delete
      parameters:
      - in: path
        name: envelopereference
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: sackReference
      responses:
        200:
          description: OK
      tags:
      - Deletes
      - Envelope
      - From
      - The
      - Content
      - Of
      - Sack
  /api/documentgeneration/sack/{sackReference}:
    delete:
      summary: deletes an envelope from the the content of a sack
      description: Deletes an envelope from the the content of a sack.
      operationId: DocumentGeneration_DeleteSackBysackReference
      x-api-path-slug: apidocumentgenerationsacksackreference-delete
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: sackReference
      responses:
        200:
          description: OK
      tags:
      - Deletes
      - Envelope
      - From
      - The
      - Content
      - Of
      - Sack
  /api/documentgeneration/processsackcontent/{sackReference}:
    get:
      summary: processes the content of the sack
      description: Processes the content of the sack.
      operationId: DocumentGeneration_ProcessSackContentBysackReference
      x-api-path-slug: apidocumentgenerationprocesssackcontentsackreference-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: sackReference
      responses:
        200:
          description: OK
      tags:
      - Processes
      - Content
      - Of
      - Sack
  /api/documentgeneration/updateemailsackcontent/{sackReference}:
    post:
      summary: updates the content of a sack
      description: Updates the content of a sack.
      operationId: DocumentGeneration_UpdateEmailSackContentBysackReferenceByemail
      x-api-path-slug: apidocumentgenerationupdateemailsackcontentsackreference-post
      parameters:
      - in: body
        name: email
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: sackReference
      responses:
        200:
          description: OK
      tags:
      - Updates
      - Content
      - Of
      - Sack
  /api/documentgeneration/updatetextsackcontent/{sackReference}:
    post:
      summary: updates the content of a sack
      description: Updates the content of a sack.
      operationId: DocumentGeneration_UpdateTextSackContentBysackReferenceBytxt
      x-api-path-slug: apidocumentgenerationupdatetextsackcontentsackreference-post
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: sackReference
      - in: body
        name: txt
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Updates
      - Content
      - Of
      - Sack
  /api/documentgeneration/updateprintsackcontent/{sackReference}:
    post:
      summary: updates the content of a sack
      description: Updates the content of a sack.
      operationId: DocumentGeneration_UpdatePrintSackContentBysackReferenceByprint
      x-api-path-slug: apidocumentgenerationupdateprintsackcontentsackreference-post
      parameters:
      - in: body
        name: print
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: sackReference
      responses:
        200:
          description: OK
      tags:
      - Updates
      - Content
      - Of
      - Sack
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