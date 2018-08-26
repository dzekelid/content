---
swagger: "2.0"
x-collection-name: Kentico Cloud
x-complete: 0
info:
  title: Kentico Cloud View a content type
  description: |-
    Retrieve a specific content type from your project by specifying its codename.

    See <https://developer.kenticocloud.com/v1/reference#view-a-content-type> for more details.
  version: 1.0.0
host: deliver.kenticocloud.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /items/3120ec15-a4a2-47ec-8ccd-c85ac8ac5ba5:
    get:
      summary: View a content item by ID
      description: Retrieve metadata information about a content item specified by
        its internal ID.
      operationId: Items3120ec15A4a247ec8ccdC85ac8ac5ba5Get
      x-api-path-slug: items3120ec15a4a247ec8ccdc85ac8ac5ba5-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - View
      - Content
      - Item
      - By
      - ID
    put:
      summary: Update a content item by ID
      description: Update an existing content item specified by its internal ID.
      operationId: Items3120ec15A4a247ec8ccdC85ac8ac5ba5Put
      x-api-path-slug: items3120ec15a4a247ec8ccdc85ac8ac5ba5-put
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Content
      - Item
      - By
      - ID
    delete:
      summary: Delete a content item by ID
      description: Delete a content item specified by its internal ID. Note that deleting
        a content item deletes all of its language variants as well.
      operationId: Items3120ec15A4a247ec8ccdC85ac8ac5ba5Delete2
      x-api-path-slug: items3120ec15a4a247ec8ccdc85ac8ac5ba5-delete
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Content
      - Item
      - By
      - ID
  /items/codename/on_roasts:
    get:
      summary: View a content item by codename
      description: Retrieve metadata information about a content item specified by
        its codename.
      operationId: ItemsCodenameOnRoastsGet
      x-api-path-slug: itemscodenameon-roasts-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - View
      - Content
      - Item
      - By
      - Codename
    put:
      summary: Update a content item by codename
      description: Update an existing content item specified by its codename.
      operationId: ItemsCodenameOnRoastsPut
      x-api-path-slug: itemscodenameon-roasts-put
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Content
      - Item
      - By
      - Codename
    delete:
      summary: Delete a content item by codename
      description: |-
        Delete a content item specified by its codename.

        Note that deleting a content item deletes all of its language variants as well.
      operationId: ItemsCodenameOnRoastsDelete
      x-api-path-slug: itemscodenameon-roasts-delete
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Content
      - Item
      - By
      - Codename
  /items/external-id/ext-cafe-brno-59713/variants/codename/en-US:
    put:
      summary: Adding localized content
      description: "Add content in a specific language to your new content item by
        performing an upsert.\r\n\r\n* In the request URL, you need to specify the
        content item you are importing to (for example, `/items/external-id/ext-cafe-brno-59713`)
        and the language of the variant (for example, `/variants/codename/en-US`).\r\n*
        The request body must contain the `elements` object in which you specify only
        the content elements you want to update. Omitted elements will remain unchanged.\r\n\r\nSee
        <https://developer.kenticocloud.com/docs/importing-to-kentico-cloud#section-2-adding-localized-content>
        for more details."
      operationId: ItemsExternalIdExtCafeBrno59713VariantsCodenameEnUSPut
      x-api-path-slug: itemsexternalidextcafebrno59713variantscodenameenus-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Ing
      - Localized
      - Content
  /items/external-id/ext-cafe-brno-59713:
    put:
      summary: Creating a content item
      description: "One of the ways to import content to your project is to send a
        PUT request to the `<cmApiUrl>/items/external-id/<your item ID>` endpoint.\r\n\r\nIn
        the body of the request, specify these properties:\r\n\r\n* `name` \u2013
        string with a display name of the new content item.\r\n* `type` \u2013 reference
        to a content type.\r\n* (Optional) `sitemap_locations` \u2013 array of references
        to sitemap locations.\r\n\r\nSee <https://developer.kenticocloud.com/docs/importing-to-kentico-cloud#section-1-creating-a-content-item>
        for more details."
      operationId: ItemsExternalIdExtCafeBrno59713Put
      x-api-path-slug: itemsexternalidextcafebrno59713-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Creating
      - Content
      - Item
  /8d155914-6674-4f17-8104-3b1c5c2b37e4/items/partner_promotion:
    get:
      summary: Displaying the right content
      description: |-
        Retrieve one personalization variant you want to display. To learn more about retrieving content, consult the [Delivery API reference](https://developer.kenticocloud.com/reference#delivery-api).

        See <https://developer.kenticocloud.com/docs/personalizing-content#section-displaying-the-right-content> for more examples.
      operationId: 8d15591466744f1781043b1c5c2b37e4ItemsPartnerPromotionGet
      x-api-path-slug: 8d15591466744f1781043b1c5c2b37e4itemspartner-promotion-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Displaying
      - Right
      - Content
  /975bf280-fd91-488c-994c-2f04416e5ee3/items/on_roasts:
    get:
      summary: Getting localized content items
      description: |-
        Get a content item in a specific language variant by using the `language` parameter.

        See [Getting localized content items](https://developer.kenticocloud.com/docs/localization#section-getting-localized-content-items) for more details.
      operationId: 975bf280Fd91488c994c2f04416e5ee3ItemsOnRoastsGet3
      x-api-path-slug: 975bf280fd91488c994c2f04416e5ee3itemson-roasts-get
      parameters:
      - in: header
        name: Content-Type
      - in: query
        name: language
      responses:
        200:
          description: OK
      tags:
      - Ting
      - Localized
      - Content
      - Items
  /items/external-id/59713:
    get:
      summary: View a content Item by external ID
      description: Retrieve metadata information about a content item specified by
        its external ID.
      operationId: ItemsExternalId59713Get
      x-api-path-slug: itemsexternalid59713-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - View
      - Content
      - Item
      - By
      - External
      - ID
    put:
      summary: Update a content item by external ID
      description: "Add a new content item or update an existing content item specified
        by its external ID.\r\n\r\n**Note:** If no content item with the specified
        external ID exists in the project, the system will try to create one. For
        existing content items, the API updates the content item's name and sitemap
        locations.\r\nYou can also specify the external ID when [adding content items](https://developer.kenticocloud.com/v1/reference#content-management-api-add-item)
        via the POST method."
      operationId: ItemsExternalId59713Put
      x-api-path-slug: itemsexternalid59713-put
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Content
      - Item
      - By
      - External
      - ID
  /975bf280-fd91-488c-994c-2f04416e5ee3/types/coffee:
    get:
      summary: View a content type
      description: |-
        Retrieve a specific content type from your project by specifying its codename.

        See <https://developer.kenticocloud.com/v1/reference#view-a-content-type> for more details.
      operationId: 975bf280Fd91488c994c2f04416e5ee3TypesCoffeeGet
      x-api-path-slug: 975bf280fd91488c994c2f04416e5ee3typescoffee-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - View
      - Content
      - Type
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