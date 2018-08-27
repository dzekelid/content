---
swagger: "2.0"
x-collection-name: RingCentral
x-complete: 0
info:
  title: RingCentral Get IVR Prompt Content
  description: |-
    Returns media content of an IVR prompt by ID.
    App Permission
    ReadAccounts
    User Permission
    ReadCompanyGreetings
    Usage Plan Group
    Medium
  version: 1.0.0
host: platform.ringcentral.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /restapi/v1.0/account/{accountId}/ivr-prompts/{promptId}/content:
    get:
      summary: Get IVR Prompt Content
      description: |-
        Returns media content of an IVR prompt by ID.
        App Permission
        ReadAccounts
        User Permission
        ReadCompanyGreetings
        Usage Plan Group
        Medium
      operationId: getPromptContent
      x-api-path-slug: restapiv1-0accountaccountidivrpromptspromptidcontent-get
      parameters:
      - in: path
        name: accountId
      - in: path
        name: promptId
      responses:
        200:
          description: OK
      tags:
      - IVR
      - Prompt
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