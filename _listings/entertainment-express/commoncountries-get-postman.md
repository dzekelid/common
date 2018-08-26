{
  "info": {
    "name": "Entertainment Express Returns a list of countries.",
    "_postman_id": "03ea3a02-95cf-49b1-99e4-b1301ea84664",
    "description": "List of Countries, ISO codes and Country IDs used throughout the API.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Common",
      "item": [
        {
          "id": "8e5eece2-b8b4-4683-98ae-1351e0fee517",
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
              "id": "5d26e00d-b322-4803-bb38-1d5256134d66"
            }
          ]
        },
        {
          "id": "18793707-7b93-4db8-bc61-fa4cfb9bfb8e",
          "name": "GetCountries",
          "request": {
            "url": "http://ee.iva-api.com/Common/Countries/",
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
            "description": "List of Countries, ISO codes and Country IDs used throughout the API."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "137c0551-995e-4290-98e5-b21d127fbf3b"
            }
          ]
        }
      ]
    }
  ]
}