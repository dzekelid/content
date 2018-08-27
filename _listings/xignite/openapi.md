swagger: "2.0"
x-collection-name: Xignite
x-complete: 1
info:
  title: Xignite VWAP
  description: provides-delayed-and-historical-volumeweightedaverage-price-vwap-information-
  version: 1.0.0
host: www.xignite.com
basePath: xVWAP.json/XigniteVWAP
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  GetReleaseContent/:
    get:
      summary: Get Release Content
      description: Return detailed information about a release as well as its content.
      operationId: getGetreleasecontent
      x-api-path-slug: getreleasecontent-get
      parameters:
      - in: query
        name: ReleaseID
        description: The press release ID>
      - in: query
        name: _Token
        description: The API Key
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Release
      - Content