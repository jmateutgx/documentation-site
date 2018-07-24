{
  "title": "Quote",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "HotelQuote",
      "name": "hotel",
      "url": "undefined/objects/hotelquote",
      "description": "Returns the total price and cancellation policies of the Option selected in the previous step (Search).",
      "isDeprecated": true,
      "args": [
        {
          "typeString": "HotelCriteriaQuoteInput!",
          "name": "criteria",
          "url": "undefined/inputobjects/hotelcriteriaquoteinput",
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
      "typeName": "Quote"
    }
  ],
  "requireby": null,
  "enumValues": null,
  "operator": "type",
  "typename": "Quote",
  "hideGithubLink": true
}
Returns the total price and cancellation policies of the Option selected in the previous step (Search).
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}
