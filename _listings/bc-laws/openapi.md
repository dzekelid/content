swagger: "2.0"
x-collection-name: BC Laws
x-complete: 1
info:
  title: BC Laws
  description: bc-laws-is-an-electronic-library-providing-free-public-access-to-the-laws-of-british-columbia--bc-laws-is-hosted-by-the-queens-printer-of-british-columbia-and-published-in-partnership-with-the-ministry-of-justice-and-the-law-clerk-of-the-legislative-assembly-bc-laws-contains-a-comprehensive-collection-of-bc-legislation-and-related-materials--it-is-available-on-the-internet-in-two-formsfirst-the-library-is-available-as-a-web-site-in-which-users-can-browse-and-search-the-laws-of-british-columbia-second-the-library-is-available-as-a-portal-to-legislation-in-raw-xml-data-format-accessible-via-the-bc-laws-api2--this-direct-access-to-raw-data-is-intended-to-enable-third-parties-to-build-or-add-their-own-custom-applications-based-on-the-structure-of-the-data-and-all-the-associated-search-functionality-inherent-in-that-structure--the-bc-laws-website-itself-is-an-example-of-one-such-application-
  termsOfService: http://www.data.gov.bc.ca/local/dbc/docs/license/API_Terms_of_Use.pdf
  version: 1.0.0
host: www.bclaws.ca
basePath: /civix
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /content/{aspectId}:
    get:
      summary: Describes the documents and directories available within a specific
        'aspect' (content group) of the BCLaws library
      description: Describes the documents and directories available within a specific
        'aspect' (content group) of the BCLaws library
      operationId: getContentAspect
      x-api-path-slug: contentaspectid-get
      parameters:
      - in: path
        name: aspectId
        description: The identifier of the aspect (content group) to search
      responses:
        200:
          description: OK
      tags:
      - Content
      - AspectId
  /content/{aspectId}/{civixDocumentId}:
    get:
      summary: Lists the metadata available for the specified index or directory from
        the BCLaws legislative respository
      description: Lists the metadata available for the specified index or directory
        from the BCLaws legislative respository
      operationId: getContentAspectCivixdocument
      x-api-path-slug: contentaspectidcivixdocumentid-get
      parameters:
      - in: path
        name: aspectId
        description: The identifier of the aspect (content group) to search
      - in: path
        name: civixDocumentId
        description: The document identification code for an index or directory
      responses:
        200:
          description: OK
      tags:
      - Content
      - AspectId
      - CivixDocumentId