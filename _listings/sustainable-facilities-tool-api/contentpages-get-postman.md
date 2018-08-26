{
  "info": {
    "name": "Sustainable Facilities Tool API Content Pages",
    "_postman_id": "c3a0a671-c281-4804-b5bd-4e31e83a23d3",
    "description": "Returns all content pages",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "content",
      "item": [
        {
          "id": "6ac12ac1-c226-4484-b2f0-6e117f8a785d",
          "name": "returnContentPages",
          "request": {
            "url": "http://api.data.gov/sftool/v1/contentpages",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns all content pages"
          },
          "response": [
            {
              "header": [
                {
                  "key": "Content-Type",
                  "value": "application/json",
                  "disabled": false
                }
              ],
              "body": "[\r\n  {\r\n    \"query\": \"query\"\r\n  }\r\n]",
              "status": "Successful response",
              "code": 200,
              "name": "Response_200",
              "id": "c39445cc-9bfd-43e1-b7eb-e3986bd0299b"
            }
          ]
        }
      ]
    }
  ]
}