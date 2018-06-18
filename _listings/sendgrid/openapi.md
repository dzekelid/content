---
swagger: "2.0"
x-collection-name: SendGrid
x-complete: 1
info:
  title: SendGrid
  description: the-sendgrid-web-api-v3-documentation--this-is-the-entirety-of-the-documented-v3-endpoints--we-have-updated-all-the-descriptions-parameters-requests-and-responses--authentication-every-endpoint-requires-authentication-in-the-form-of-an-authorization-header-authorization-bearer-api-key
  version: 1.0.0
host: api.sendgrid.com
basePath: /v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /mail_settings/plain_content:
    get:
      summary: Get Mail Settings Plain Content
      description: "**This endpoint allows you to retrieve your current Plain Content
        mail settings.**\n\nThe plain content setting will automatically convert any
        plain text emails that you send to HTML before sending.\n\nMail settings allow
        you to tell SendGrid specific things to do to every email that you send to
        your recipients over SendGrid\u2019s [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html)
        or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html)."
      operationId: mail_settings.plain_content.get
      x-api-path-slug: mail-settingsplain-content-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - Mail
      - Settings
      - Plain
      - Content
    patch:
      summary: Patch Mail Settings Plain Content
      description: "**This endpoint allows you to update your current Plain Content
        mail settings.**\n\nThe plain content setting will automatically convert any
        plain text emails that you send to HTML before sending.\n\nMail settings allow
        you to tell SendGrid specific things to do to every email that you send to
        your recipients over SendGrid\u2019s [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html)
        or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html)."
      operationId: mail_settings.plain_content.patch
      x-api-path-slug: mail-settingsplain-content-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - Mail
      - Settings
      - Plain
      - Content
---