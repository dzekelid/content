---
swagger: "2.0"
x-collection-name: Atlassian
x-complete: 0
info:
  title: Confluence Cloud API Get content restriction status for group
  description: "Returns whether the specified content restriction applies to a group.
    \nFor example, if the 'admins' group has permission to read a page with an \nID
    of 123, then the following request will return true:\n\n`https://your-domain.atlassian.net/wiki/rest/api/content/123/restriction/byOperation/read/group/admins`\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \nPermission to view the content."
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
  /content/{id}/child/{type}:
    get:
      summary: Get content children by type
      description: "Returns all children of a given type, for a piece of content.
        \nA piece of content has different types of child content, depending on its
        type:\n\n- `page`: child content is `page`, `comment`, `attachment`\n- `blogpost`:
        child content is `comment`, `attachment`\n- `attachment`: child content is
        `comment`\n- `comment`: child content is `attachment`\n\nCustom content types
        that are provided by apps can also be returned.\n\nNote, this method only
        returns direct children. To return children at all \nlevels, use [Get descendants
        by type](#api-content-id-descendant-type-get).\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
        required**: 'View' permission for the space, \nand permission to view the
        content if it is a page."
      operationId: com.atlassian.confluence.plugins.restapi.resources.ChildContentResource.getContentChildrenByType_get
      x-api-path-slug: contentidchildtype-get
      parameters:
      - in: query
        name: expand
        description: A multi-value parameter indicating which properties of the new
          content to expand
      - in: path
        name: id
        description: The ID of the content to be queried for its children
      - in: query
        name: limit
        description: The maximum number of content to return per page
      - in: query
        name: parentVersion
        description: The version of the parent content to retrieve children for
      - in: query
        name: start
        description: The starting index of the returned content
      - in: path
        name: type
        description: The type of children to return
      responses:
        200:
          description: OK
      tags:
      - Content
      - Children
      - By
      - Type
  /content/{id}/descendant:
    get:
      summary: Get content descendants
      description: "Returns a map of the descendants of a piece of content. This is
        similar \nto [Get content children](#api-content-id-child-get), except that
        this \nmethod returns child pages at all levels, rather than just the direct
        \nchild pages.\n\nA piece of content has different types of descendants, depending
        on its type:\n\n- `page`: descendant is `page`, `comment`, `attachment`\n-
        `blogpost`: descendant is `comment`, `attachment`\n- `attachment`: descendant
        is `comment`\n- `comment`: descendant is `attachment`\n\nThe map will always
        include all descendant types that are valid for the content. \nHowever, if
        the content has no instances of a descendant type, the map will \ncontain
        an empty array for that descendant type.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
        required**: \n'View' permission for the space, and permission to view the
        content if it \nis a page."
      operationId: com.atlassian.confluence.plugins.restapi.resources.DescendantContentResource.getContentDescendants_g
      x-api-path-slug: contentiddescendant-get
      parameters:
      - in: query
        name: expand
        description: A multi-value parameter indicating which properties of the children
          to expand, where:- `attachment` returns all attachments for the content
      - in: path
        name: id
        description: The ID of the content to be queried for its descendants
      responses:
        200:
          description: OK
      tags:
      - Content
      - Descendants
  /content/{id}/descendant/{type}:
    get:
      summary: Get content descendants by type
      description: "Returns all descendants of a given type, for a piece of content.
        This is \nsimilar to [Get content children by type](#api-content-id-child-type-get),
        \nexcept that this method returns child pages at all levels, rather than just
        \nthe direct child pages.\n\nA piece of content has different types of descendants,
        depending on its type:\n\n- `page`: descendant is `page`, `comment`, `attachment`\n-
        `blogpost`: descendant is `comment`, `attachment`\n- `attachment`: descendant
        is `comment`\n- `comment`: descendant is `attachment`\n\nCustom content types
        that are provided by apps can also be returned.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
        required**: \n'View' permission for the space, and permission to view the
        content if it \nis a page."
      operationId: com.atlassian.confluence.plugins.restapi.resources.DescendantContentResource.descendantsOfType_get
      x-api-path-slug: contentiddescendanttype-get
      parameters:
      - in: query
        name: expand
        description: A multi-value parameter indicating which properties of the new
          content to expand
      - in: path
        name: id
        description: The ID of the content to be queried for its descendants
      - in: query
        name: limit
        description: The maximum number of content to return per page
      - in: query
        name: start
        description: The starting index of the returned content
      - in: path
        name: type
        description: The type of descendants to return
      responses:
        200:
          description: OK
      tags:
      - Content
      - Descendants
      - By
      - Type
  /content/{id}/label:
    post:
      summary: Add labels to content
      description: "Adds labels to a piece of content. Does not modify the existing
        labels.\n\nNotes:\n\n- Labels can also be added when creating content ([Create
        content](#api-content-post)).\n- Labels can be updated when updating content
        ([Update content](#api-content-id-put)). \nThis will delete the existing labels
        and replace them with the labels in \nthe request.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
        required**: \nPermission to update the content."
      operationId: com.atlassian.confluence.plugins.restapi.resources.ContentLabelsResource.addLabelsToContent_post
      x-api-path-slug: contentidlabel-post
      parameters:
      - in: path
        name: id
        description: The ID of the content that will have labels added to it
      responses:
        200:
          description: OK
      tags:
      - Labels
      - To
      - Content
    delete:
      summary: Remove label from content using query parameter
      description: "Removes a label from a piece of content. This is similar to \n[Remove
        label from content](#api-content-id-label-label-delete) \nexcept that the
        label name is specified via a query parameter. \n\nUse this method if the
        label name has \"/\" characters, as \n[Remove label from content using query
        parameter](#api-content-id-label-delete) \ndoes not accept \"/\" characters
        for the label name.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
        required**: \nPermission to update the content."
      operationId: com.atlassian.confluence.plugins.restapi.resources.ContentLabelsResource.removeLabelFromContentUsing
      x-api-path-slug: contentidlabel-delete
      parameters:
      - in: path
        name: id
        description: The ID of the content that the label will be removed from
      - in: query
        name: name
        description: The name of the label to be removed
      responses:
        200:
          description: OK
      tags:
      - Remove
      - Label
      - From
      - Content
      - Using
      - Query
      - Parameter
  /content/{id}/label/{label}:
    delete:
      summary: Remove label from content
      description: "Removes a label from a piece of content. This is similar to \n[Remove
        label from content using query parameter](#api-content-id-label-delete) \nexcept
        that the label name is specified via a path parameter. \n\nUse this method
        if the label name does not have \"/\" characters, as the path \nparameter
        does not accept \"/\" characters for security reasons. Otherwise, \nuse [Remove
        label from content using query parameter](#api-content-id-label-delete).\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
        required**: \nPermission to update the content."
      operationId: com.atlassian.confluence.plugins.restapi.resources.ContentLabelsResource.removeLabelFromContent_dele
      x-api-path-slug: contentidlabellabel-delete
      parameters:
      - in: path
        name: id
        description: The ID of the content that the label will be removed from
      - in: path
        name: label
        description: The name of the label to be removed
      responses:
        200:
          description: OK
      tags:
      - Remove
      - Label
      - From
      - Content
  /content/{id}/property:
    get:
      summary: Get content properties
      description: "Returns the properties for a piece of content. For more information
        \nabout content properties, see [Content properties in the REST API](https://developer.atlassian.com/cloud/confluence/content-properties/).\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
        required**: \n'View' permission for the space, and permission to view the
        content if it is a page."
      operationId: com.atlassian.confluence.plugins.restapi.resources.ContentPropertyResource.getContentProperties_get
      x-api-path-slug: contentidproperty-get
      parameters:
      - in: query
        name: expand
        description: A multi-value parameter indicating which properties of the content
          to expand
      - in: path
        name: id
        description: The ID of the content to be queried for its properties
      - in: query
        name: limit
        description: The maximum number of properties to return per page
      - in: query
        name: start
        description: The starting index of the returned properties
      responses:
        200:
          description: OK
      tags:
      - Content
      - Properties
    post:
      summary: Create content property
      description: "Creates a property for an existing piece of content. For more
        information \nabout content properties, see [Content properties in the REST
        API](https://developer.atlassian.com/cloud/confluence/content-properties/).\n\nThis
        is the same as [Create content property for key](#api-content-id-property-key-post)
        \nexcept that the key is specified in the request body instead of as a \npath
        parameter.\n\nContent properties can also be added when creating a new piece
        of content \nby including them in the `metadata.properties` of the request.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
        required**: \nPermission to update the content."
      operationId: com.atlassian.confluence.plugins.restapi.resources.ContentPropertyResource.createContentProperty_pos
      x-api-path-slug: contentidproperty-post
      parameters:
      - in: path
        name: id
        description: The ID of the content to add the property to
      responses:
        200:
          description: OK
      tags:
      - Content
      - Property
  /content/{id}/property/{key}:
    get:
      summary: Get content property
      description: "Returns a content property for a piece of content. For more information,
        see \n[Content properties in the REST API](https://developer.atlassian.com/cloud/confluence/content-properties/).\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
        required**: \n'View' permission for the space, and permission to view the
        content if it is a page."
      operationId: com.atlassian.confluence.plugins.restapi.resources.ContentPropertyResource.getContentProperty_get
      x-api-path-slug: contentidpropertykey-get
      parameters:
      - in: query
        name: expand
        description: A multi-value parameter indicating which properties of the content
          to expand
      - in: path
        name: id
        description: The ID of the content to be queried for the property
      - in: path
        name: key
        description: The key of the content property
      responses:
        200:
          description: OK
      tags:
      - Content
      - Property
    post:
      summary: Create content property for key
      description: "Creates a property for an existing piece of content. For more
        information \nabout content properties, see [Content properties in the REST
        API](https://developer.atlassian.com/cloud/confluence/content-properties/).\n\nThis
        is the same as [Create content property](#api-content-id-property-post) \nexcept
        that the key is specified as a path parameter instead of in the \nrequest
        body.\n\nContent properties can also be added when creating a new piece of
        content \nby including them in the `metadata.properties` of the request.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
        required**: \nPermission to update the content."
      operationId: com.atlassian.confluence.plugins.restapi.resources.ContentPropertyResource.createContentPropertyForK
      x-api-path-slug: contentidpropertykey-post
      parameters:
      - in: path
        name: id
        description: The ID of the content to add the property to
      - in: path
        name: key
        description: The key of the content property
      responses:
        200:
          description: OK
      tags:
      - Content
      - Propertykey
    put:
      summary: Update content property
      description: "Updates an existing content property. This method will also create
        a new \nproperty for a piece of content, if the property key does not exist
        and \nthe property version is 1. For more information about content properties,
        see \n[Content properties in the REST API](https://developer.atlassian.com/cloud/confluence/content-properties/).\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
        required**: \nPermission to update the content."
      operationId: com.atlassian.confluence.plugins.restapi.resources.ContentPropertyResource.updateContentProperty_put
      x-api-path-slug: contentidpropertykey-put
      parameters:
      - in: path
        name: id
        description: The ID of the content that the property belongs to
      - in: path
        name: key
        description: The key of the property
      responses:
        200:
          description: OK
      tags:
      - Content
      - Property
    delete:
      summary: Delete content property
      description: "Deletes a content property. For more information about content
        properties, see \n[Content properties in the REST API](https://developer.atlassian.com/cloud/confluence/content-properties/).\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
        required**: \nPermission to update the content."
      operationId: com.atlassian.confluence.plugins.restapi.resources.ContentPropertyResource.deleteContentProperty_del
      x-api-path-slug: contentidpropertykey-delete
      parameters:
      - in: path
        name: id
        description: The ID of the content that the property belongs to
      - in: path
        name: key
        description: The key of the property
      responses:
        200:
          description: OK
      tags:
      - Content
      - Property
  /content/{id}/restriction/byOperation/{operationKey}/group/{groupName}:
    get:
      summary: Get content restriction status for group
      description: "Returns whether the specified content restriction applies to a
        group. \nFor example, if the 'admins' group has permission to read a page
        with an \nID of 123, then the following request will return true:\n\n`https://your-domain.atlassian.net/wiki/rest/api/content/123/restriction/byOperation/read/group/admins`\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
        required**: \nPermission to view the content."
      operationId: com.atlassian.confluence.plugins.restapi.resources.ContentRestrictionResource.getContentRestrictionS
      x-api-path-slug: contentidrestrictionbyoperationoperationkeygroupgroupname-get
      parameters:
      - in: path
        name: groupName
        description: The name of the group to be queried for whether the content restriction
          applies to it
      - in: path
        name: id
        description: The ID of the content that the restriction applies to
      - in: path
        name: operationKey
        description: The operation that the restriction applies to
      responses:
        200:
          description: OK
      tags:
      - Content
      - Restriction
      - Statusgroup
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