{
  "info": {
    "name": "Entertainment Express List of image types contained in the database.",
    "_postman_id": "34995f2f-1e27-479a-a56c-8809f1bf54b0",
    "description": "A list of image types available in the IVA database. **EX: Poster**",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Common",
      "item": [
        {
          "id": "3f792a4a-88a3-4ed6-a2d4-f1e3700604c3",
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
              "id": "7d97f94a-4b74-425f-af01-ad5ede528273"
            }
          ]
        },
        {
          "id": "2f7ff940-4e96-4750-9dbd-35883ccae038",
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
              "id": "009aec91-3e43-4598-b13f-1a5490b6c756"
            }
          ]
        },
        {
          "id": "fbaa2542-f8dd-4acc-b275-4c88775438bc",
          "name": "GetImageTypes",
          "request": {
            "url": "http://ee.iva-api.com/Common/ImageTypes/",
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
            "description": "A list of image types available in the IVA database. **EX: Poster**"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1739a4b5-9fd6-44f8-b4d9-a6ae74011b92"
            }
          ]
        }
      ]
    }
  ]
}