{
  "info": {
    "name": "Sustainable Facilities Tool API Content Page",
    "_postman_id": "2ffcbdd0-60d8-4e22-a0c8-1d9885d6b94e",
    "description": "Returns a content page by parameter.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "content",
      "item": [
        {
          "id": "f3db540b-ee31-4b23-ac7b-40618e7b6020",
          "name": "returnContentPage",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.data.gov",
              "path": [
                "sftool",
                "v1",
                "contentpages/:parameter"
              ],
              "variable": [
                {
                  "id": "parameter",
                  "value": "parameter",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a content page by parameter"
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
              "id": "182277a3-f7aa-4158-9e28-b3b21bd097ec"
            }
          ]
        }
      ]
    }
  ]
}