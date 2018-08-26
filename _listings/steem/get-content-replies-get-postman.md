{
  "info": {
    "name": "Steem get content replies",
    "_postman_id": "e79ccbb8-3db9-4085-b12d-22c09ef59fb7",
    "description": "get content replies",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Get",
      "item": [
        {
          "id": "0885645c-3cee-4f6f-ac5e-a54db7335568",
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
              "id": "6f6725df-847b-4727-b558-9806a37b9856"
            }
          ]
        },
        {
          "id": "9bc32062-4247-4774-b78f-22a26eb85143",
          "name": "get-content-replies",
          "request": {
            "url": "http://api.steemjs.com/get_content_replies?author=%7B%7D&permlink=%7B%7D",
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
            "description": "get content replies"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bee5a201-8534-4ee3-ab1e-0629ad2d2dc0"
            }
          ]
        }
      ]
    }
  ]
}