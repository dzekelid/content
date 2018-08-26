{
  "info": {
    "name": "Steem get content",
    "_postman_id": "13ac5d5f-471e-4fdf-9deb-b46ba587c93c",
    "description": "get content",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Get",
      "item": [
        {
          "id": "deb63c35-3388-42c8-b1d9-531d27e2d17c",
          "name": "get-content",
          "request": {
            "url": "http://api.steemjs.com/get_content?author=%7B%7D&permlink=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "get content"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7d1f06e4-68b1-4f2c-bca9-7fe237a10ce0"
            }
          ]
        }
      ]
    }
  ]
}