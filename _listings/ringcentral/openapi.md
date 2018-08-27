swagger: "2.0"
x-collection-name: RingCentral
x-complete: 1
info:
  title: RingCentral Connect Platform API Explorer
  description: this-is-an-interactive-api-explorer-for-the-ringcentral-connect-platform--to-use-this-service-you-will-need-to-have-a-developer-account---links--a-hrefhttpsnetstorage-ringcentral-comdpwapiexplorerrcplatform-basic-ymlv20180514092722-target-blankringcentral-api-specaspannbspnbspopenapi-fka-swagger-formatnbspnbspnbspnbspspana-hrefhttpsgithub-comoaiopenapispecification-target-blanklearn-more-about-openapia
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