---
swagger: "2.0"
x-collection-name: Atlassian
x-complete: 0
info:
  title: Confluence Cloud API Get content comments
  description: "Returns the comments on a piece of content.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: 'View' permission for the space, \nand permission to view the content
    if it is a page."
  termsOfService: http://atlassian.com/terms/
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /content:
    get:
      summary: Get content
      description: "Returns all content in a Confluence instance.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
        required**: \nPermission to access the Confluence site ('Can use' global permission).
        \nOnly content that the user has permission to view will be returned."
      operationId: com.atlassian.confluence.plugins.restapi.resources.ContentResource.getContent_get
      x-api-path-slug: content-get
      parameters:
      - in: query
        name: expand
        description: A multi-value parameter indicating which properties of the content
          to expand
      - in: query
        name: limit
        description: The maximum number of content objects to return per page
      - in: query
        name: orderby
        description: Orders the content by a particular field
      - in: query
        name: postingDay
        description: The posting date of the blog post to be returned
      - in: query
        name: spaceKey
        description: The key of the space to be queried for its content
      - in: query
        name: start
        description: The starting index of the returned content
      - in: query
        name: status
        description: Filter the results to a set of content based on their status
      - in: query
        name: title
        description: The title of the page to be returned
      - in: query
        name: trigger
        description: If set to `viewed`, the request will trigger a viewed event for
          the content
      - in: query
        name: type
        description: The type of content to return
      responses:
        200:
          description: OK
      tags:
      - Content
    post:
      summary: Create content
      description: "Creates a new piece of content or publishes an existing draft.
        \n\nTo publish a draft, add the `id` and `status` properties to the body of
        the request. \nSet the `id` to the ID of the draft and set the `status` to
        'current'. When the \nrequest is sent, a new piece of content will be created
        and the metadata from the \ndraft will be transferred into it.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
        required**: 'Add' permission for the \nspace that the content will be created
        in, and permission to view the draft if publishing a draft."
      operationId: com.atlassian.confluence.plugins.restapi.resources.ContentResource.createContent_post
      x-api-path-slug: content-post
      parameters:
      - in: query
        name: expand
        description: A multi-value parameter indicating which properties of the new
          content to expand
      - in: query
        name: status
        description: Filter the returned content by status
      responses:
        200:
          description: OK
      tags:
      - Content
  /content/search:
    get:
      summary: Search content by CQL
      description: "Returns the list of content that matches a Confluence Query Language
        \n(CQL) query. For information on CQL, see: \n[Advanced searching using CQL](https://developer.atlassian.com/cloud/confluence/advanced-searching-using-cql/).\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
        required**: \nPermission to access the Confluence site ('Can use' global permission).
        \nOnly content that the user has permission to view will be returned."
      operationId: com.atlassian.confluence.plugins.restapi.resources.ContentResource.searchContentByCQL_get
      x-api-path-slug: contentsearch-get
      parameters:
      - in: query
        name: cql
        description: The CQL string that is used to find the requested content
      - in: query
        name: cqlcontext
        description: The space, content, and content status to execute the search
          against
      - in: query
        name: expand
        description: A multi-value parameter indicating which properties of the content
          to expand
      - in: query
        name: limit
        description: The maximum number of content objects to return per page
      - in: query
        name: start
        description: The starting index of the returned content
      responses:
        200:
          description: OK
      tags:
      - Search
      - Content
      - By
      - CQL
  /content/{id}:
    get:
      summary: Get content by ID
      description: "Returns a single piece of content, like a page or a blog post.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
        required**: \nPermission to view the content. If the content is a blog post,
        'View' permission \nfor the space is required."
      operationId: com.atlassian.confluence.plugins.restapi.resources.ContentResource.getContentById_get
      x-api-path-slug: contentid-get
      parameters:
      - in: query
        name: embeddedContentRender
        description: The version of embedded content (e
      - in: query
        name: expand
        description: A multi-value parameter indicating which properties of the content
          to expand
      - in: path
        name: id
        description: The ID of the content to be returned
      - in: query
        name: status
        description: Filter the results to a set of content based on their status
      - in: query
        name: trigger
        description: If set to `viewed`, the request will trigger a viewed event for
          the content
      - in: query
        name: version
        description: The version number of the content to be returned
      responses:
        200:
          description: OK
      tags:
      - Content
      - By
      - ID
    put:
      summary: Update content
      description: "Updates a piece of content. Use this method to update the title
        or body \nof a piece of content, change the status, change the parent page,
        and more.\n\nNote, updating draft content is currently not supported.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
        required**: \nPermission to update the content."
      operationId: com.atlassian.confluence.plugins.restapi.resources.ContentResource.updateContent_put
      x-api-path-slug: contentid-put
      parameters:
      - in: query
        name: conflictPolicy
        description: The action that should be taken when conflicts are discovered
      - in: path
        name: id
        description: The ID of the content to be updated
      - in: query
        name: status
        description: The updated status of the content
      responses:
        200:
          description: OK
      tags:
      - Content
    delete:
      summary: Delete content
      description: "Moves a piece of content to the space's trash or purges it from
        the trash, \ndepending on the content's type and status:\n\n- If the content's
        type is `page` or `blogpost` and its status is `current`, \nit will be trashed.\n-
        If the content's type is `page` or `blogpost` and its status is `trashed`,
        \nthe content will be purged from the trash and deleted permanently. Note,
        \nyou must also set the `status` query parameter to `trashed` in your request.\n-
        If the content's type is `comment` or `attachment`, it will be deleted \npermanently
        without being trashed.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
        required**: \n'Delete' permission for the space that the content is in, and
        permission to edit the content."
      operationId: com.atlassian.confluence.plugins.restapi.resources.ContentResource.deleteContent_delete
      x-api-path-slug: contentid-delete
      parameters:
      - in: path
        name: id
        description: The ID of the content to be deleted
      - in: query
        name: status
        description: Set this to `trashed`, if the contents status is `trashed` and
          you want to purge it
      responses:
        200:
          description: OK
      tags:
      - Content
  /content/{id}/child:
    get:
      summary: Get content children
      description: "Returns a map of the direct children of a piece of content. A
        piece of content \nhas different types of child content, depending on its
        type. These are \nthe default parent-child content type relationships:\n\n-
        `page`: child content is `page`, `comment`, `attachment`\n- `blogpost`: child
        content is `comment`, `attachment`\n- `attachment`: child content is `comment`\n-
        `comment`: child content is `attachment`\n\nApps can override these default
        relationships. Apps can also introduce \nnew content types that create new
        parent-child content relationships.\n\nNote, the map will always include all
        child content types that are valid \nfor the content. However, if the content
        has no instances of a child content \ntype, the map will contain an empty
        array for that child content type.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
        required**: 'View' permission for the space, \nand permission to view the
        content if it is a page."
      operationId: com.atlassian.confluence.plugins.restapi.resources.ChildContentResource.getContentChildren_get
      x-api-path-slug: contentidchild-get
      parameters:
      - in: query
        name: expand
        description: A multi-value parameter indicating which properties of the children
          to expand, where:- `attachment` returns all attachments for the content
      - in: path
        name: id
        description: The ID of the content to be queried for its children
      - in: query
        name: parentVersion
        description: The version of the parent content to retrieve children for
      responses:
        200:
          description: OK
      tags:
      - Content
      - Children
  /content/{id}/child/comment:
    get:
      summary: Get content comments
      description: "Returns the comments on a piece of content.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
        required**: 'View' permission for the space, \nand permission to view the
        content if it is a page."
      operationId: com.atlassian.confluence.plugins.restapi.resources.ChildContentResource.getContentComments_get
      x-api-path-slug: contentidchildcomment-get
      parameters:
      - in: query
        name: depth
        description: Currently, this parameter is not used
      - in: query
        name: expand
        description: A multi-value parameter indicating which properties of the attachments
          to expand
      - in: path
        name: id
        description: The ID of the content to be queried for its comments
      - in: query
        name: limit
        description: The maximum number of comments to return per page
      - in: query
        name: location
        description: The location of the comments in the page
      - in: query
        name: parentVersion
        description: The version of the parent content to retrieve children for
      - in: query
        name: start
        description: The starting index of the returned comments
      responses:
        200:
          description: OK
      tags:
      - Content
      - Comments
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