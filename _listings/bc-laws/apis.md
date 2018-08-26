---
name: BC Laws
x-slug: bc-laws
description: 'BC Laws is an electronic library providing free public access to the
  laws of British Columbia. BC Laws is hosted by the Queen&rsquo;s Printer of British
  Columbia and published in partnership with the Ministry of Justice and the Law Clerk
  of the Legislative Assembly. BC Laws contains a comprehensive collection of BC legislation
  and related materials. It is available on the internet in two forms: First: The
  library is available as a web site in which users can browse and search the laws
  of British Columbia. Second: The library is available as a portal to legislation
  in raw XML1 data format, accessible via the BC Laws API2. This direct access to
  raw data is intended to enable third parties to build or add their own custom applications
  based on the structure of the data and all the associated search functionality inherent
  in that structure. The BC Laws website itself is an example of one such application.'
image: ""
x-kinRank: "7"
x-alexaRank: "0"
tags: Content
created: "2018-08-26"
modified: "2018-08-26"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/bc-laws/apis.md
specificationVersion: "0.14"
apis:
- name: BC Laws - Describes the documents and directories available within a specific
    'aspect' (content group) of the BCLaws library
  x-api-slug: contentaspectid-get
  description: Describes the documents and directories available within a specific
    'aspect' (content group) of the BCLaws library
  image: ""
  humanURL: http://bclaws.ca
  baseURL: https://www.bclaws.ca//civix
  tags: Laws, State Government, API Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/bc-laws/contentaspectid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/bc-laws/contentaspectid-get-openapi.md
- name: BC Laws - Lists the metadata available for the specified index or directory
    from the BCLaws legislative respository
  x-api-slug: contentaspectidcivixdocumentid-get
  description: Lists the metadata available for the specified index or directory from
    the BCLaws legislative respository
  image: ""
  humanURL: http://bclaws.ca
  baseURL: https://www.bclaws.ca//civix
  tags: Laws, State Government, API Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/bc-laws/contentaspectidcivixdocumentid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/bc-laws/contentaspectidcivixdocumentid-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://bc.geographical.names.api.gallery.streamdata.io
- type: x-api-stack
  url: http://bc.laws.stack.network
- type: x-website
  url: http://bclaws.ca
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---