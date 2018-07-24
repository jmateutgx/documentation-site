{
  "title": "Booking",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "HotelBooking",
      "name": "hotel",
      "url": "undefined/objects/hotelbooking",
      "description": "Returns detailed information about books, you can indicated a list of locators or a range date.",
      "isDeprecated": true,
      "args": [
        {
          "typeString": "HotelCriteriaBookingInput!",
          "name": "criteria",
          "url": "undefined/inputobjects/hotelcriteriabookinginput",
          "description": ""
        },
        {
          "typeString": "HotelSettingsInput",
          "name": "settings",
          "url": "undefined/inputobjects/hotelsettingsinput",
          "description": ""
        }
      ],
      "deprecationReason": "You can find it in query at HotelX",
      "descriptionSplitted": {
        "date": "2017-11-21",
        "first": "deprecated from",
        "second": "You can find it in query at HotelX"
      },
      "deprecationDate": "2017-11-21",
      "typeName": "Booking"
    }
  ],
  "requireby": null,
  "enumValues": null,
  "operator": "type",
  "typename": "Booking",
  "hideGithubLink": true
}
Returns detailed information about books.
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}
