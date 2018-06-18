---
name: Instructure
x-slug: instructure
description: Instructure makes software that makes smarter people. Products include
  Canvas LMS, Bridge and Canvas Network.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
x-kinRank: "8"
x-alexaRank: "367"
tags: Content
created: "2018-06-18"
modified: "2018-06-18"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/apis.md
specificationVersion: "0.14"
apis:
- name: Instructure Canvas Courses API List content exports
  x-api-slug: instructure-canvas-courses-api
  description: List content exports.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/content_exports
  tags: Courses,Course,Id,Content,Exports
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/coursescourse-idcontent-exports-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/coursescourse-idcontent-exports-get-openapi.md
- name: Instructure Canvas Courses API Export content
  x-api-slug: instructure-canvas-courses-api
  description: Export content.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/content_exports
  tags: Courses,Course,Id,Content,Exports
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/coursescourse-idcontent-exports-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/coursescourse-idcontent-exports-post-openapi.md
- name: Instructure Canvas Courses API Show content export
  x-api-slug: instructure-canvas-courses-api
  description: Show content export.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/content_exports/id
  tags: Courses,Course,Id,Content,Exports,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/coursescourse-idcontent-exportsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/coursescourse-idcontent-exportsid-get-openapi.md
- name: Instructure Canvas Courses API List licenses
  x-api-slug: instructure-canvas-courses-api
  description: List licenses.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/content_licenses
  tags: Courses,Course,Id,Content,Licenses
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/coursescourse-idcontent-licenses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/coursescourse-idcontent-licenses-get-openapi.md
- name: Instructure Canvas Courses API List content migrations
  x-api-slug: instructure-canvas-courses-api
  description: List content migrations.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/content_migrations
  tags: Courses,Course,Id,Content,Migrations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/coursescourse-idcontent-migrations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/coursescourse-idcontent-migrations-get-openapi.md
- name: Instructure Canvas Courses API Create a content migration
  x-api-slug: instructure-canvas-courses-api
  description: Create a content migration.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/content_migrations
  tags: Courses,Course,Id,Content,Migrations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/coursescourse-idcontent-migrations-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/coursescourse-idcontent-migrations-post-openapi.md
- name: Instructure Canvas Courses API List migration issues
  x-api-slug: instructure-canvas-courses-api
  description: List migration issues.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/content_migrations/content_migration_id/migration_issues
  tags: Courses,Course,Id,Content,Migrations,Content,Migration,Id,Migration,Issues
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/coursescourse-idcontent-migrationscontent-migration-idmigration-issues-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/coursescourse-idcontent-migrationscontent-migration-idmigration-issues-get-openapi.md
- name: Instructure Canvas Courses API Get a migration issue
  x-api-slug: instructure-canvas-courses-api
  description: Get a migration issue.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/content_migrations/content_migration_id/migration_issues/{id}
  tags: Courses,Course,Id,Content,Migrations,Content,Migration,Id,Migration,Issues,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/coursescourse-idcontent-migrationscontent-migration-idmigration-issuesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/coursescourse-idcontent-migrationscontent-migration-idmigration-issuesid-get-openapi.md
- name: Instructure Canvas Courses API Update a migration issue
  x-api-slug: instructure-canvas-courses-api
  description: Update a migration issue.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/content_migrations/content_migration_id/migration_issues/{id}
  tags: Courses,Course,Id,Content,Migrations,Content,Migration,Id,Migration,Issues,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/coursescourse-idcontent-migrationscontent-migration-idmigration-issuesid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/coursescourse-idcontent-migrationscontent-migration-idmigration-issuesid-put-openapi.md
- name: Instructure Canvas Courses API Get a content migration
  x-api-slug: instructure-canvas-courses-api
  description: Get a content migration.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/content_migrations/id
  tags: Courses,Course,Id,Content,Migrations,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/coursescourse-idcontent-migrationsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/coursescourse-idcontent-migrationsid-get-openapi.md
- name: Instructure Canvas Courses API Update a content migration
  x-api-slug: instructure-canvas-courses-api
  description: Update a content migration.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/content_migrations/id
  tags: Courses,Course,Id,Content,Migrations,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/coursescourse-idcontent-migrationsid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/coursescourse-idcontent-migrationsid-put-openapi.md
- name: Instructure Canvas Courses API List Migration Systems
  x-api-slug: instructure-canvas-courses-api
  description: List migration systems.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/content_migrations/migrators
  tags: Courses,Course,Id,Content,Migrations,Migrators
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/coursescourse-idcontent-migrationsmigrators-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/coursescourse-idcontent-migrationsmigrators-get-openapi.md
- name: Instructure Canvas Courses API Reset a course
  x-api-slug: instructure-canvas-courses-api
  description: Reset a course.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/reset_content
  tags: Courses,Course,Id,Reset,Content
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/coursescourse-idreset-content-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/coursescourse-idreset-content-post-openapi.md
- name: Instructure Canvas Courses API
  x-api-slug: instructure-canvas-courses-api
  description: Instructure makes software that makes smarter people. Products include
    Canvas LMS, Bridge and Canvas Network.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1
  tags: Content
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/openapi.md
- name: Instructure Canvas Groups API List content exports
  x-api-slug: instructure-canvas-groups-api
  description: List content exports.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//groups/{group_id}/content_exports
  tags: Groups,Group,Id,Content,Exports
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/groupsgroup-idcontent-exports-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/groupsgroup-idcontent-exports-get-openapi.md
- name: Instructure Canvas Groups API Export content
  x-api-slug: instructure-canvas-groups-api
  description: Export content.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//groups/{group_id}/content_exports
  tags: Groups,Group,Id,Content,Exports
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/groupsgroup-idcontent-exports-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/groupsgroup-idcontent-exports-post-openapi.md
- name: Instructure Canvas Groups API Show content export
  x-api-slug: instructure-canvas-groups-api
  description: Show content export.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//groups/{group_id}/content_exports/id
  tags: Groups,Group,Id,Content,Exports,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/groupsgroup-idcontent-exportsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/groupsgroup-idcontent-exportsid-get-openapi.md
- name: Instructure Canvas Groups API List licenses
  x-api-slug: instructure-canvas-groups-api
  description: List licenses.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//groups/{group_id}/content_licenses
  tags: Groups,Group,Id,Content,Licenses
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/groupsgroup-idcontent-licenses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/groupsgroup-idcontent-licenses-get-openapi.md
- name: Instructure Canvas Groups API List content migrations
  x-api-slug: instructure-canvas-groups-api
  description: List content migrations.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//groups/{group_id}/content_migrations
  tags: Groups,Group,Id,Content,Migrations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/groupsgroup-idcontent-migrations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/groupsgroup-idcontent-migrations-get-openapi.md
- name: Instructure Canvas Groups API Create a content migration
  x-api-slug: instructure-canvas-groups-api
  description: Create a content migration.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//groups/{group_id}/content_migrations
  tags: Groups,Group,Id,Content,Migrations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/groupsgroup-idcontent-migrations-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/groupsgroup-idcontent-migrations-post-openapi.md
- name: Instructure Canvas Groups API List migration issues
  x-api-slug: instructure-canvas-groups-api
  description: List migration issues.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//groups/{group_id}/content_migrations/content_migration_id/migration_issues
  tags: Groups,Group,Id,Content,Migrations,Content,Migration,Id,Migration,Issues
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/groupsgroup-idcontent-migrationscontent-migration-idmigration-issues-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/groupsgroup-idcontent-migrationscontent-migration-idmigration-issues-get-openapi.md
- name: Instructure Canvas Groups API Get a migration issue
  x-api-slug: instructure-canvas-groups-api
  description: Get a migration issue.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//groups/{group_id}/content_migrations/content_migration_id/migration_issues/{id}
  tags: Groups,Group,Id,Content,Migrations,Content,Migration,Id,Migration,Issues,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/groupsgroup-idcontent-migrationscontent-migration-idmigration-issuesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/groupsgroup-idcontent-migrationscontent-migration-idmigration-issuesid-get-openapi.md
- name: Instructure Canvas Groups API Update a migration issue
  x-api-slug: instructure-canvas-groups-api
  description: Update a migration issue.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//groups/{group_id}/content_migrations/content_migration_id/migration_issues/{id}
  tags: Groups,Group,Id,Content,Migrations,Content,Migration,Id,Migration,Issues,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/groupsgroup-idcontent-migrationscontent-migration-idmigration-issuesid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/groupsgroup-idcontent-migrationscontent-migration-idmigration-issuesid-put-openapi.md
- name: Instructure Canvas Groups API Get a content migration
  x-api-slug: instructure-canvas-groups-api
  description: Get a content migration.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//groups/{group_id}/content_migrations/id
  tags: Groups,Group,Id,Content,Migrations,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/groupsgroup-idcontent-migrationsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/groupsgroup-idcontent-migrationsid-get-openapi.md
- name: Instructure Canvas Groups API Update a content migration
  x-api-slug: instructure-canvas-groups-api
  description: Update a content migration.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//groups/{group_id}/content_migrations/id
  tags: Groups,Group,Id,Content,Migrations,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/groupsgroup-idcontent-migrationsid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/groupsgroup-idcontent-migrationsid-put-openapi.md
- name: Instructure Canvas Groups API List Migration Systems
  x-api-slug: instructure-canvas-groups-api
  description: List migration systems.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//groups/{group_id}/content_migrations/migrators
  tags: Groups,Group,Id,Content,Migrations,Migrators
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/groupsgroup-idcontent-migrationsmigrators-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/groupsgroup-idcontent-migrationsmigrators-get-openapi.md
- name: Instructure Canvas Groups API
  x-api-slug: instructure-canvas-groups-api
  description: Instructure makes software that makes smarter people. Products include
    Canvas LMS, Bridge and Canvas Network.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1
  tags: Content
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/openapi.md
- name: Instructure Canvas Users API List content exports
  x-api-slug: instructure-canvas-users-api
  description: List content exports.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//users/{user_id}/content_exports
  tags: Users,User,Id,Content,Exports
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/usersuser-idcontent-exports-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/usersuser-idcontent-exports-get-openapi.md
- name: Instructure Canvas Users API Export content
  x-api-slug: instructure-canvas-users-api
  description: Export content.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//users/{user_id}/content_exports
  tags: Users,User,Id,Content,Exports
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/usersuser-idcontent-exports-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/usersuser-idcontent-exports-post-openapi.md
- name: Instructure Canvas Users API Show content export
  x-api-slug: instructure-canvas-users-api
  description: Show content export.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//users/{user_id}/content_exports/id
  tags: Users,User,Id,Content,Exports,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/usersuser-idcontent-exportsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/usersuser-idcontent-exportsid-get-openapi.md
- name: Instructure Canvas Users API List licenses
  x-api-slug: instructure-canvas-users-api
  description: List licenses.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//users/{user_id}/content_licenses
  tags: Users,User,Id,Content,Licenses
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/usersuser-idcontent-licenses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/usersuser-idcontent-licenses-get-openapi.md
- name: Instructure Canvas Users API List content migrations
  x-api-slug: instructure-canvas-users-api
  description: List content migrations.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//users/{user_id}/content_migrations
  tags: Users,User,Id,Content,Migrations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/usersuser-idcontent-migrations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/usersuser-idcontent-migrations-get-openapi.md
- name: Instructure Canvas Users API Create a content migration
  x-api-slug: instructure-canvas-users-api
  description: Create a content migration.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//users/{user_id}/content_migrations
  tags: Users,User,Id,Content,Migrations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/usersuser-idcontent-migrations-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/usersuser-idcontent-migrations-post-openapi.md
- name: Instructure Canvas Users API List migration issues
  x-api-slug: instructure-canvas-users-api
  description: List migration issues.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//users/{user_id}/content_migrations/content_migration_id/migration_issues
  tags: Users,User,Id,Content,Migrations,Content,Migration,Id,Migration,Issues
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/usersuser-idcontent-migrationscontent-migration-idmigration-issues-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/usersuser-idcontent-migrationscontent-migration-idmigration-issues-get-openapi.md
- name: Instructure Canvas Users API Get a migration issue
  x-api-slug: instructure-canvas-users-api
  description: Get a migration issue.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//users/{user_id}/content_migrations/content_migration_id/migration_issues/{id}
  tags: Users,User,Id,Content,Migrations,Content,Migration,Id,Migration,Issues,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/usersuser-idcontent-migrationscontent-migration-idmigration-issuesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/usersuser-idcontent-migrationscontent-migration-idmigration-issuesid-get-openapi.md
- name: Instructure Canvas Users API Update a migration issue
  x-api-slug: instructure-canvas-users-api
  description: Update a migration issue.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//users/{user_id}/content_migrations/content_migration_id/migration_issues/{id}
  tags: Users,User,Id,Content,Migrations,Content,Migration,Id,Migration,Issues,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/usersuser-idcontent-migrationscontent-migration-idmigration-issuesid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/usersuser-idcontent-migrationscontent-migration-idmigration-issuesid-put-openapi.md
- name: Instructure Canvas Users API Get a content migration
  x-api-slug: instructure-canvas-users-api
  description: Get a content migration.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//users/{user_id}/content_migrations/id
  tags: Users,User,Id,Content,Migrations,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/usersuser-idcontent-migrationsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/usersuser-idcontent-migrationsid-get-openapi.md
- name: Instructure Canvas Users API Update a content migration
  x-api-slug: instructure-canvas-users-api
  description: Update a content migration.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//users/{user_id}/content_migrations/id
  tags: Users,User,Id,Content,Migrations,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/usersuser-idcontent-migrationsid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/usersuser-idcontent-migrationsid-put-openapi.md
- name: Instructure Canvas Users API List Migration Systems
  x-api-slug: instructure-canvas-users-api
  description: List migration systems.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//users/{user_id}/content_migrations/migrators
  tags: Users,User,Id,Content,Migrations,Migrators
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/usersuser-idcontent-migrationsmigrators-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/usersuser-idcontent-migrationsmigrators-get-openapi.md
- name: Instructure Canvas Users API
  x-api-slug: instructure-canvas-users-api
  description: Instructure makes software that makes smarter people. Products include
    Canvas LMS, Bridge and Canvas Network.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1
  tags: Content
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/instructure/openapi.md
x-common:
- type: x-blog
  url: http://blog.instructure.com
- type: x-blog-rss
  url: http://voice.instructure.com/CMS/UI/Modules/BizBlogger/rss.aspx?tabid=772438&moduleid=1638884&maxcount=25&t=415c2e5d197a4d6f7cdcc81385b677f1
- type: x-crunchbase
  url: https://crunchbase.com/organization/instructure
- type: x-crunchbase
  url: http://www.crunchbase.com/company/instructure
- type: x-email
  url: info@instructure.com
- type: x-email
  url: jobs@instructure.com
- type: x-email
  url: privacy@instructure.com
- type: x-email
  url: legal@instructure.com
- type: x-github
  url: https://github.com/instructure
- type: x-twitter
  url: https://twitter.com/instructure
- type: x-website
  url: http://instructure.com
- type: x-website
  url: https://canvas.instructure.com/doc/api/index.html
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---