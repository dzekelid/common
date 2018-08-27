{
  "info": {
    "name": "Entertainment Express Gets all languages.",
    "_postman_id": "d864bcad-3a2d-4ddf-9d78-51e56bcdfd33",
    "description": "Returns a list of languages used in the API as well as the ISO code and language ID.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Common",
      "item": [
        {
          "id": "cf158886-fca3-45a0-96c5-a7550d2bbda1",
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
              "id": "35ecaab6-d531-4974-99cf-1cbcbf44b779"
            }
          ]
        },
        {
          "id": "d35d4c87-c6df-4972-a6a1-6478086631b5",
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
              "id": "bee7defd-3673-4adb-869b-023ff88aca75"
            }
          ]
        },
        {
          "id": "62d6d4cb-1e59-4314-b3c3-70576b50a55f",
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
              "id": "6b3a002c-2718-443c-bb8a-e8e9807dd73a"
            }
          ]
        },
        {
          "id": "94e790be-772d-4c17-9494-92824190dc34",
          "name": "GetLanguages",
          "request": {
            "url": "http://ee.iva-api.com/Common/Languages/",
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
            "description": "Returns a list of languages used in the API as well as the ISO code and language ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "62f78299-bc4a-4fa8-8d09-0041f5623570"
            }
          ]
        }
      ]
    }
  ]
}