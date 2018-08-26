---
swagger: "2.0"
x-collection-name: Steem
x-complete: 0
info:
  title: Steem get content replies
  description: get content replies
  version: 1.0.0
host: api.steemjs.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /get_content:
    get:
      summary: get content
      description: get content
      operationId: get-content
      x-api-path-slug: get-content-get
      parameters:
      - in: query
        name: author
        description: author
      - in: query
        name: permlink
        description: permlink
      responses:
        200:
          description: OK
      tags:
      - Get
      - Content
  /get_content_replies:
    get:
      summary: get content replies
      description: get content replies
      operationId: get-content-replies
      x-api-path-slug: get-content-replies-get
      parameters:
      - in: query
        name: author
        description: author
      - in: query
        name: permlink
        description: permlink
      responses:
        200:
          description: OK
      tags:
      - Get
      - Content
      - Replies
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