---
swagger: "2.0"
x-collection-name: GitHub
x-complete: 1
info:
  title: GitHub
  description: github-is-the-best-place-to-share-code-with-friends-coworkers-classmates-and-complete-strangers--over-24-million-people-use-github-to-build-amazing-things-together-across-67-million-repositories--with-the-collaborative-features-of-github-com-and-github-business-it-has-never-been-easier-for-individuals-and-teams-to-write-faster-better-code-
  termsOfService: https://help.github.com/articles/github-terms-of-service/#b-api-terms
  version: 1.0.0
host: api.github.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /repos/{owner}/{repo}/contents/{path}:
    delete:
      summary: Delete Repos Owner Repo Contents Path
      description: |-
        Delete a file.
        This method deletes a file in a repository.
      operationId: delete-a-filethis-method-deletes-a-file-in-a-repository
      x-api-path-slug: reposownerrepocontentspath-delete
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: path
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Contents
      - Path
    get:
      summary: Get Repos Owner Repo Contents Path
      description: |-
        Get contents.
        This method returns the contents of a file or directory in a repository.
        Files and symlinks support a custom media type for getting the raw content.
        Directories and submodules do not support custom media types.
        Note: This API supports files up to 1 megabyte in size.
        Here can be many outcomes. For details see "http://developer.github.com/v3/repos/contents/"
      operationId: get-contentsthis-method-returns-the-contents-of-a-file-or-directory-in-a-repositoryfiles-and-symlink
      x-api-path-slug: reposownerrepocontentspath-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: path
      - in: query
        name: path
        description: The content path
      - in: query
        name: ref
        description: The String name of the Commit/Branch/Tag
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Contents
      - Path
    put:
      summary: Put Repos Owner Repo Contents Path
      description: Create a file.
      operationId: create-a-file
      x-api-path-slug: reposownerrepocontentspath-put
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: path
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Contents
      - Path
---