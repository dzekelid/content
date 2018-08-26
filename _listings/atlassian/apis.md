---
name: Atlassian
x-slug: atlassian
description: Millions of users globally rely on Atlassian products every day for improving
  software development, project management, collaboration, and code quality.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
x-kinRank: "8"
x-alexaRank: "1656"
tags: Content
created: "2018-08-26"
modified: "2018-08-26"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/apis.md
specificationVersion: "0.14"
apis:
- name: The Confluence Cloud REST API - Get content
  x-api-slug: content-get
  description: "Returns all content in a Confluence instance.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \nPermission to access the Confluence site ('Can use' global permission).
    \nOnly content that the user has permission to view will be returned."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/content-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/content-get-openapi.md
- name: The Confluence Cloud REST API - Search content by CQL
  x-api-slug: contentsearch-get
  description: "Returns the list of content that matches a Confluence Query Language
    \n(CQL) query. For information on CQL, see: \n[Advanced searching using CQL](https://developer.atlassian.com/cloud/confluence/advanced-searching-using-cql/).\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \nPermission to access the Confluence site ('Can use' global permission).
    \nOnly content that the user has permission to view will be returned."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentsearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentsearch-get-openapi.md
- name: The Confluence Cloud REST API - Get content by ID
  x-api-slug: contentid-get
  description: "Returns a single piece of content, like a page or a blog post.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \nPermission to view the content. If the content is a blog post, 'View'
    permission \nfor the space is required."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentid-get-openapi.md
- name: The Confluence Cloud REST API - Update content
  x-api-slug: contentid-put
  description: "Updates a piece of content. Use this method to update the title or
    body \nof a piece of content, change the status, change the parent page, and more.\n\nNote,
    updating draft content is currently not supported.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \nPermission to update the content."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentid-put-openapi.md
- name: The Confluence Cloud REST API - Delete content
  x-api-slug: contentid-delete
  description: "Moves a piece of content to the space's trash or purges it from the
    trash, \ndepending on the content's type and status:\n\n- If the content's type
    is `page` or `blogpost` and its status is `current`, \nit will be trashed.\n-
    If the content's type is `page` or `blogpost` and its status is `trashed`, \nthe
    content will be purged from the trash and deleted permanently. Note, \nyou must
    also set the `status` query parameter to `trashed` in your request.\n- If the
    content's type is `comment` or `attachment`, it will be deleted \npermanently
    without being trashed.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \n'Delete' permission for the space that the content is in, and permission
    to edit the content."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentid-delete-openapi.md
- name: The Confluence Cloud REST API - Get content children
  x-api-slug: contentidchild-get
  description: "Returns a map of the direct children of a piece of content. A piece
    of content \nhas different types of child content, depending on its type. These
    are \nthe default parent-child content type relationships:\n\n- `page`: child
    content is `page`, `comment`, `attachment`\n- `blogpost`: child content is `comment`,
    `attachment`\n- `attachment`: child content is `comment`\n- `comment`: child content
    is `attachment`\n\nApps can override these default relationships. Apps can also
    introduce \nnew content types that create new parent-child content relationships.\n\nNote,
    the map will always include all child content types that are valid \nfor the content.
    However, if the content has no instances of a child content \ntype, the map will
    contain an empty array for that child content type.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: 'View' permission for the space, \nand permission to view the content
    if it is a page."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentidchild-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentidchild-get-openapi.md
- name: The Confluence Cloud REST API - Get content comments
  x-api-slug: contentidchildcomment-get
  description: "Returns the comments on a piece of content.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: 'View' permission for the space, \nand permission to view the content
    if it is a page."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentidchildcomment-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentidchildcomment-get-openapi.md
- name: The Confluence Cloud REST API - Get content children by type
  x-api-slug: contentidchildtype-get
  description: "Returns all children of a given type, for a piece of content. \nA
    piece of content has different types of child content, depending on its type:\n\n-
    `page`: child content is `page`, `comment`, `attachment`\n- `blogpost`: child
    content is `comment`, `attachment`\n- `attachment`: child content is `comment`\n-
    `comment`: child content is `attachment`\n\nCustom content types that are provided
    by apps can also be returned.\n\nNote, this method only returns direct children.
    To return children at all \nlevels, use [Get descendants by type](#api-content-id-descendant-type-get).\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: 'View' permission for the space, \nand permission to view the content
    if it is a page."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentidchildtype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentidchildtype-get-openapi.md
- name: The Confluence Cloud REST API - Get content descendants
  x-api-slug: contentiddescendant-get
  description: "Returns a map of the descendants of a piece of content. This is similar
    \nto [Get content children](#api-content-id-child-get), except that this \nmethod
    returns child pages at all levels, rather than just the direct \nchild pages.\n\nA
    piece of content has different types of descendants, depending on its type:\n\n-
    `page`: descendant is `page`, `comment`, `attachment`\n- `blogpost`: descendant
    is `comment`, `attachment`\n- `attachment`: descendant is `comment`\n- `comment`:
    descendant is `attachment`\n\nThe map will always include all descendant types
    that are valid for the content. \nHowever, if the content has no instances of
    a descendant type, the map will \ncontain an empty array for that descendant type.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \n'View' permission for the space, and permission to view the content
    if it \nis a page."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentiddescendant-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentiddescendant-get-openapi.md
- name: The Confluence Cloud REST API - Get content descendants by type
  x-api-slug: contentiddescendanttype-get
  description: "Returns all descendants of a given type, for a piece of content. This
    is \nsimilar to [Get content children by type](#api-content-id-child-type-get),
    \nexcept that this method returns child pages at all levels, rather than just
    \nthe direct child pages.\n\nA piece of content has different types of descendants,
    depending on its type:\n\n- `page`: descendant is `page`, `comment`, `attachment`\n-
    `blogpost`: descendant is `comment`, `attachment`\n- `attachment`: descendant
    is `comment`\n- `comment`: descendant is `attachment`\n\nCustom content types
    that are provided by apps can also be returned.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \n'View' permission for the space, and permission to view the content
    if it \nis a page."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentiddescendanttype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentiddescendanttype-get-openapi.md
- name: The Confluence Cloud REST API - Add labels to content
  x-api-slug: contentidlabel-post
  description: "Adds labels to a piece of content. Does not modify the existing labels.\n\nNotes:\n\n-
    Labels can also be added when creating content ([Create content](#api-content-post)).\n-
    Labels can be updated when updating content ([Update content](#api-content-id-put)).
    \nThis will delete the existing labels and replace them with the labels in \nthe
    request.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw) required**:
    \nPermission to update the content."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentidlabel-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentidlabel-post-openapi.md
- name: The Confluence Cloud REST API - Remove label from content using query parameter
  x-api-slug: contentidlabel-delete
  description: "Removes a label from a piece of content. This is similar to \n[Remove
    label from content](#api-content-id-label-label-delete) \nexcept that the label
    name is specified via a query parameter. \n\nUse this method if the label name
    has \"/\" characters, as \n[Remove label from content using query parameter](#api-content-id-label-delete)
    \ndoes not accept \"/\" characters for the label name.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \nPermission to update the content."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentidlabel-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentidlabel-delete-openapi.md
- name: The Confluence Cloud REST API - Remove label from content
  x-api-slug: contentidlabellabel-delete
  description: "Removes a label from a piece of content. This is similar to \n[Remove
    label from content using query parameter](#api-content-id-label-delete) \nexcept
    that the label name is specified via a path parameter. \n\nUse this method if
    the label name does not have \"/\" characters, as the path \nparameter does not
    accept \"/\" characters for security reasons. Otherwise, \nuse [Remove label from
    content using query parameter](#api-content-id-label-delete).\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \nPermission to update the content."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentidlabellabel-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentidlabellabel-delete-openapi.md
- name: The Confluence Cloud REST API - Get content properties
  x-api-slug: contentidproperty-get
  description: "Returns the properties for a piece of content. For more information
    \nabout content properties, see [Content properties in the REST API](https://developer.atlassian.com/cloud/confluence/content-properties/).\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \n'View' permission for the space, and permission to view the content
    if it is a page."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentidproperty-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentidproperty-get-openapi.md
- name: The Confluence Cloud REST API - Create content property
  x-api-slug: contentidproperty-post
  description: "Creates a property for an existing piece of content. For more information
    \nabout content properties, see [Content properties in the REST API](https://developer.atlassian.com/cloud/confluence/content-properties/).\n\nThis
    is the same as [Create content property for key](#api-content-id-property-key-post)
    \nexcept that the key is specified in the request body instead of as a \npath
    parameter.\n\nContent properties can also be added when creating a new piece of
    content \nby including them in the `metadata.properties` of the request.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \nPermission to update the content."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentidproperty-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentidproperty-post-openapi.md
- name: The Confluence Cloud REST API - Get content property
  x-api-slug: contentidpropertykey-get
  description: "Returns a content property for a piece of content. For more information,
    see \n[Content properties in the REST API](https://developer.atlassian.com/cloud/confluence/content-properties/).\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \n'View' permission for the space, and permission to view the content
    if it is a page."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentidpropertykey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentidpropertykey-get-openapi.md
- name: The Confluence Cloud REST API - Create content property for key
  x-api-slug: contentidpropertykey-post
  description: "Creates a property for an existing piece of content. For more information
    \nabout content properties, see [Content properties in the REST API](https://developer.atlassian.com/cloud/confluence/content-properties/).\n\nThis
    is the same as [Create content property](#api-content-id-property-post) \nexcept
    that the key is specified as a path parameter instead of in the \nrequest body.\n\nContent
    properties can also be added when creating a new piece of content \nby including
    them in the `metadata.properties` of the request.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \nPermission to update the content."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentidpropertykey-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentidpropertykey-post-openapi.md
- name: The Confluence Cloud REST API - Update content property
  x-api-slug: contentidpropertykey-put
  description: "Updates an existing content property. This method will also create
    a new \nproperty for a piece of content, if the property key does not exist and
    \nthe property version is 1. For more information about content properties, see
    \n[Content properties in the REST API](https://developer.atlassian.com/cloud/confluence/content-properties/).\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \nPermission to update the content."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentidpropertykey-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentidpropertykey-put-openapi.md
- name: The Confluence Cloud REST API - Delete content property
  x-api-slug: contentidpropertykey-delete
  description: "Deletes a content property. For more information about content properties,
    see \n[Content properties in the REST API](https://developer.atlassian.com/cloud/confluence/content-properties/).\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \nPermission to update the content."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentidpropertykey-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentidpropertykey-delete-openapi.md
- name: The Confluence Cloud REST API - Get content restriction status for group
  x-api-slug: contentidrestrictionbyoperationoperationkeygroupgroupname-get
  description: "Returns whether the specified content restriction applies to a group.
    \nFor example, if the 'admins' group has permission to read a page with an \nID
    of 123, then the following request will return true:\n\n`https://your-domain.atlassian.net/wiki/rest/api/content/123/restriction/byOperation/read/group/admins`\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \nPermission to view the content."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentidrestrictionbyoperationoperationkeygroupgroupname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentidrestrictionbyoperationoperationkeygroupgroupname-get-openapi.md
- name: The Confluence Cloud REST API - Add group to content restriction
  x-api-slug: contentidrestrictionbyoperationoperationkeygroupgroupname-put
  description: "Adds a group to a content restriction. That is, grant read or update
    \npermission to the group for a piece of content.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \nPermission to edit the content."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentidrestrictionbyoperationoperationkeygroupgroupname-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentidrestrictionbyoperationoperationkeygroupgroupname-put-openapi.md
- name: The Confluence Cloud REST API - Remove group from content restriction
  x-api-slug: contentidrestrictionbyoperationoperationkeygroupgroupname-delete
  description: "Removes a group from a content restriction. That is, remove read or
    update \npermission for the group for a piece of content.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \nPermission to edit the content."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentidrestrictionbyoperationoperationkeygroupgroupname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentidrestrictionbyoperationoperationkeygroupgroupname-delete-openapi.md
- name: The Confluence Cloud REST API - Get content restriction status for user
  x-api-slug: contentidrestrictionbyoperationoperationkeyuser-get
  description: "Returns whether the specified content restriction applies to a user.
    \nFor example, if the user 'admin' has permission to read a page with an \nID
    of 123, then the following request will return true:\n\n`https://your-domain.atlassian.net/wiki/rest/api/content/123/restriction/byOperation/read/user?username=admin`\n\nOne
    of `key`, `username`, or `accountId` must be specified as a query \nparameter
    to identify the user.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \nPermission to view the content."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentidrestrictionbyoperationoperationkeyuser-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentidrestrictionbyoperationoperationkeyuser-get-openapi.md
- name: The Confluence Cloud REST API - Add user to content restriction
  x-api-slug: contentidrestrictionbyoperationoperationkeyuser-put
  description: "Adds a user to a content restriction. That is, grant read or update
    \npermission to the user for a piece of content.\n\nOne of `key`, `username`,
    or `accountId` must be specified as a query \nparameter to identify the user.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \nPermission to edit the content."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentidrestrictionbyoperationoperationkeyuser-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentidrestrictionbyoperationoperationkeyuser-put-openapi.md
- name: The Confluence Cloud REST API - Remove user from content restriction
  x-api-slug: contentidrestrictionbyoperationoperationkeyuser-delete
  description: "Removes a group from a content restriction. That is, remove read or
    update \npermission for the group for a piece of content.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \nPermission to edit the content."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentidrestrictionbyoperationoperationkeyuser-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentidrestrictionbyoperationoperationkeyuser-delete-openapi.md
- name: The Confluence Cloud REST API - Get content versions
  x-api-slug: contentidversion-get
  description: "Returns the versions for a piece of content in descending order.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \nPermission to view the content. If the content is a blog post, 'View'
    permission \nfor the space is required."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentidversion-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentidversion-get-openapi.md
- name: The Confluence Cloud REST API - Restore content version
  x-api-slug: contentidversion-post
  description: "Restores a historical version to be the latest version. That is, a
    new version \nis created with the content of the historical version.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \nPermission to update the content."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentidversion-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentidversion-post-openapi.md
- name: The Confluence Cloud REST API - Get content version
  x-api-slug: contentidversionversionnumber-get
  description: "Returns a version for a piece of content.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \nPermission to view the content. If the content is a blog post, 'View'
    permission \nfor the space is required."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentidversionversionnumber-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentidversionversionnumber-get-openapi.md
- name: The Confluence Cloud REST API - Delete content version
  x-api-slug: contentidversionversionnumber-delete
  description: "Delete a historical version. This does not delete the changes made
    to the \ncontent in that version, rather the changes for the deleted version are
    \nrolled up into the next version. Note, you cannot delete the current version.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \nPermission to update the content."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentidversionversionnumber-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentidversionversionnumber-delete-openapi.md
- name: The Confluence Cloud REST API - Convert content body
  x-api-slug: contentbodyconvertto-post
  description: |-
    Converts a content body from one format to another format.

    Supported conversions:

    - storage: view, export_view, styled_view, editor
    - editor: storage
    - view: none
    - export_view: none
    - styled_view: none

    **[Permissions](https://confluence.atlassian.com/x/_AozKw) required**:
    If request specifies 'contentIdContext', 'View' permission for the space, and permission to view the content.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentbodyconvertto-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/contentbodyconvertto-post-openapi.md
- name: The Confluence Cloud REST API - Get content by type for space
  x-api-slug: spacespacekeycontenttype-get
  description: |-
    Returns all content of a given type, in a space. The returned content is
    ordered by content ID in ascending order.

    **[Permissions](https://confluence.atlassian.com/x/_AozKw) required**:
    'View' permission for the space. Note, the returned list will only
    contain content that the current user has permission to view.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/spacespacekeycontenttype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/spacespacekeycontenttype-get-openapi.md
- name: The Confluence Cloud REST API - Create content template
  x-api-slug: template-post
  description: "Creates a new content template. Note, blueprint templates cannot be
    created via the REST API.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \n'Admin' permission for the space to create a space template or 'Confluence
    Administrator' \nglobal permission to create a global template."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/template-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/template-post-openapi.md
- name: The Confluence Cloud REST API - Update content template
  x-api-slug: template-put
  description: "Updates a content template. Note, blueprint templates cannot be updated\nvia
    the REST API.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw) required**:
    \n'Admin' permission for the space to create a space template or 'Confluence Administrator'
    \nglobal permission to create a global template."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/template-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/template-put-openapi.md
- name: The Confluence Cloud REST API - Get content templates
  x-api-slug: templatepage-get
  description: "Returns all content templates. Use this method to retrieve all global\ncontent
    templates or all content templates in a space.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \n'Admin' permission for the space to view space templates and 'Confluence
    \nAdministrator' global permission to view global templates."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/templatepage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/templatepage-get-openapi.md
- name: The Confluence Cloud REST API - Get content template
  x-api-slug: templatecontenttemplateid-get
  description: "Returns a content template. This includes information about template,
    \nlike the name, the space or blueprint that the template is in, the body \nof
    the template, and more.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \n'Admin' permission for the space to view space templates and 'Confluence
    \nAdministrator' global permission to view global templates."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/templatecontenttemplateid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/templatecontenttemplateid-get-openapi.md
- name: The Confluence Cloud REST API - Get content watch status
  x-api-slug: userwatchcontentcontentid-get
  description: "Returns whether a user is watching a piece of content. Choose the
    user by \ndoing one of the following:\n\n- Specify a user via a query parameter:
    Use the `username`, `key`, or `accountId` \nto identify the user. The user making
    the request must be a Confluence administrator.\n- Do not specify a user: The
    currently logged-in user will be used.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \n'Confluence Administrator' global permission if specifying a user,
    otherwise \npermission to access the Confluence site ('Can use' global permission)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/userwatchcontentcontentid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/userwatchcontentcontentid-get-openapi.md
- name: The Confluence Cloud REST API - Add content watcher
  x-api-slug: userwatchcontentcontentid-post
  description: "Adds a user as a watcher to a piece of content. Choose the user by
    doing \none of the following:\n\n- Specify a user via a query parameter: Use the
    `username`, `key`, or `accountId` \nto identify the user. The user making the
    request must be a Confluence administrator.\n- Do not specify a user: The currently
    logged-in user will be used.\n\nNote, you must add the `X-Atlassian-Token: no-check`
    header when making a \nrequest, as this operation has XSRF protection.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \n'Confluence Administrator' global permission if specifying a user,
    otherwise \npermission to access the Confluence site ('Can use' global permission)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/userwatchcontentcontentid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/userwatchcontentcontentid-post-openapi.md
- name: The Confluence Cloud REST API - Remove content watcher
  x-api-slug: userwatchcontentcontentid-delete
  description: "Removes a user as a watcher from a piece of content. Choose the user
    by \ndoing one of the following:\n\n- Specify a user via a query parameter: Use
    the `username`, `key`, or `accountId` \nto identify the user. The user making
    the request must be a Confluence administrator.\n- Do not specify a user: The
    currently logged-in user will be used.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \n'Confluence Administrator' global permission if specifying a user,
    otherwise \npermission to access the Confluence site ('Can use' global permission)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/userwatchcontentcontentid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/userwatchcontentcontentid-delete-openapi.md
- name: Jira Cloud REST API - Create issue type avatar
  x-api-slug: api2issuetypeidavatar2-post
  description: |-
    Creates an avatar for the issue type. Specify the avatar's local file location as binary data in the body of the request. Also, include the following headers:

    *   `X-Atlassian-Token: no-check`
    *   `Content-Type: image/_image type_` Valid image types are JPEG, GIF, or PNG.

    For example: `curl --request POST \ --user email@example.com: \ --header 'X-Atlassian-Token: no-check' \ --header 'Content-Type: image/< image_type>' \ --data-binary "" \ --url 'https://your-domain.atlassian.net/rest/api/2/issuetype/{issueTypeId}'This` The avatar is cropped to a square. If no crop parameters are specified, the square originates at the top left of the image. The length of the square's sides is set to the smaller of the height or width of the image. The cropped image is then used to create avatars of 16x16, 24x24, 32x32, and 48x48 in size. After creating the avatar, use [Update issue type](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-issuetype-id-put) to set it as the issue type's active avatar. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](href=).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/api2issuetypeidavatar2-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/atlassian/api2issuetypeidavatar2-post-openapi.md
x-common:
- type: x-openapi
  url: https://developer.atlassian.com/cloud/jira/platform/swagger.v3.json
- type: x-openapi
  url: https://developer.atlassian.com/cloud/confluence/swagger.v3.json
- type: x-openapi
  url: https://developer.atlassian.com/cloud/jira/software/swagger.v3.json
- type: x-openapi
  url: https://developer.atlassian.com/cloud/jira/service-desk/swagger.v3.json
- type: x-website
  url: http://atlassian.com/
- type: x-website
  url: http://www.atlassian.com
- type: x-api-gallery
  url: http://att.dev.program.api.gallery.streamdata.io
- type: x-api-stack
  url: http://atlassian.stack.network
- type: x-blog
  url: http://blogs.atlassian.com/
- type: x-crunchbase
  url: https://crunchbase.com/organization/atlassian
- type: x-crunchbase
  url: http://www.crunchbase.com/company/atlassian
- type: x-email
  url: copyright@atlassian.com
- type: x-email
  url: trademarks@atlassian.com
- type: x-email
  url: sales@atlassian.com
- type: x-email
  url: ar_enterprise@atlassian.com
- type: x-email
  url: privacy@atlassian.com
- type: x-email
  url: eudatarep@atlassian.com
- type: x-email
  url: experts@atlassian.com
- type: x-email
  url: remittance@atlassian.com
- type: x-email
  url: ap@atlassian.com
- type: x-email
  url: procurement@atlassian.com
- type: x-github
  url: https://github.com/atlassian
- type: x-privacy-policy
  url: https://www.atlassian.com/legal/privacy-policy?_ga=2.188884514.868776184.1519225620-845241124.1519225620
- type: x-twitter
  url: https://twitter.com/atlassian
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---