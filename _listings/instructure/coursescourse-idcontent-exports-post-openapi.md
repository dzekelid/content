---
swagger: "2.0"
x-collection-name: Instructure
x-complete: 0
info:
  title: Instructure Canvas Courses API Export content
  description: Export content.
  termsOfService: https://www.canvaslms.com/policies/api-policy
  version: v1
host: canvas.instructure.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /courses/{course_id}/content_exports:
    get:
      summary: List content exports
      description: List content exports.
      operationId: list-content-exports
      x-api-path-slug: coursescourse-idcontent-exports-get
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Content
      - Exports
    post:
      summary: Export content
      description: Export content.
      operationId: export-content
      x-api-path-slug: coursescourse-idcontent-exports-post
      parameters:
      - in: query
        name: export_type
        description: u201ccommon_cartridgeu201dnnExport the contents of the course
          in the Common Cartridge (
      - in: query
        name: skip_notifications
        description: Don&#39;t send the notifications about the export to the user
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Content
      - Exports
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