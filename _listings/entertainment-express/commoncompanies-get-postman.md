{
  "info": {
    "name": "Entertainment Express Paged list of companies.",
    "_postman_id": "388da40a-b94b-4556-b48f-4cec2af92bbb",
    "description": "Companies are listed in a movie, show, or game response as those whom are involved with the program.  EX: Universal Pictures.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Common",
      "item": [
        {
          "id": "19ce9fde-b5a3-418c-8fbf-d58f14012c5b",
          "name": "GetCompanies",
          "request": {
            "url": "http://ee.iva-api.com/Common/Companies/?Skip=%7B%7D&Take=%7B%7D",
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
            "description": "Companies are listed in a movie, show, or game response as those whom are involved with the program.  EX: Universal Pictures."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1c9a350e-5d99-4001-a0e4-9292f398bdd5"
            }
          ]
        }
      ]
    }
  ]
}