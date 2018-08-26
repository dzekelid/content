---
swagger: "2.0"
x-collection-name: Open Science Framework
x-complete: 1
info:
  title: Open Science Framework
  description: osf-provides-free-and-open-source-project-management-support-for-researchers-across-the-entire-research-lifecycle--as-a-collaboration-tool-osf-helps-researchers-work-on-projects-privately-with-a-limited-number-of-collaborators-and-make-parts-of-their-projects-public-or-make-all-the-project-publicly-accessible-for-broader-dissemination--as-a-workflow-system-osf-enables-connections-to-the-many-services-researchers-already-use-to-streamline-their-process-and-increase-efficiency--as-a-flexible-repository-it-can-store-and-archive-research-data-protocols-and-materials--
  contact:
    name: OSF
    url: https://osf.io/support
    email: support@osf.io
  version: "2.0"
host: test-api.osf.io
basePath: /v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /wikis/{wiki_id}/content/:
    get:
      summary: Retrieve the Content of a Wiki
      description: |-
        Retrieves the plaintext content of a wiki in markdown format.
        ####Returns
        Returns `text/markdown` of the wiki content itself.
        If the request is unsuccessful, plaintext with the error message will be displayed.
      operationId: wiki_content
      x-api-path-slug: wikiswiki-idcontent-get
      parameters:
      - in: path
        name: wiki_id
        description: The unique identifier of the wiki
      responses:
        200:
          description: OK
      tags:
      - Wikis
      - Wiki
      - Content
---