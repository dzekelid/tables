{
  "info": {
    "name": "Eventbrite Get System Countries",
    "_postman_id": "a8541090-7612-40c8-93da-19f6100227a9",
    "description": "Returns a single page response with a key of countries,\ncontaining a list of countries.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Checkout",
      "item": [
        {
          "id": "1cd3169b-4e9c-4330-a187-748c5b41dd75",
          "name": "getCheckoutSettingsCountriesCurrencies",
          "request": {
            "url": "http://www.eventbriteapi.com/v3/checkout_settings/countries_currencies/",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get the countries and currencies which are supported by Eventbrite for ticket payment"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f81563f6-a877-4e99-800e-7c685b024880"
            }
          ]
        }
      ]
    },
    {
      "name": "System",
      "item": [
        {
          "id": "4aa3d8c3-ce02-47ff-87b6-3dd18c2b9d22",
          "name": "getSystemCountries",
          "request": {
            "url": "http://www.eventbriteapi.com/v3/system/countries/",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a single page response with a key of countries,\ncontaining a list of countries."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "766ca02c-1ddd-49b7-98a1-9cd61bcc65f4"
            }
          ]
        }
      ]
    }
  ]
}