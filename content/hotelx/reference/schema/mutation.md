{
  "title": "HotelXMutation",
  "description": "",
  "weight": 2,
  "fields": [
    {
      "typeString": "HotelBookPayload",
      "name": "book",
      "url": "/hotelx/reference/objects/hotelbookpayload",
      "description": "Creates a new hotel booking consisting of an option of 1 or more rooms.",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "HotelBookInput!",
          "name": "input",
          "url": "/hotelx/reference/inputobjects/hotelbookinput",
          "description": ""
        },
        {
          "typeString": "HotelSettingsInput",
          "name": "settings",
          "url": "/hotelx/reference/inputobjects/hotelsettingsinput",
          "description": ""
        }
      ]
    },
    {
      "typeString": "HotelCancelPayload",
      "name": "cancel",
      "url": "/hotelx/reference/objects/hotelcancelpayload",
      "description": "Cancels an existing hotel booking consisting of an option of 1 or more rooms.",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "HotelCancelInput!",
          "name": "input",
          "url": "/hotelx/reference/inputobjects/hotelcancelinput",
          "description": ""
        },
        {
          "typeString": "HotelSettingsInput",
          "name": "settings",
          "url": "/hotelx/reference/inputobjects/hotelsettingsinput",
          "description": ""
        }
      ]
    },
    {
      "typeString": "String!",
      "name": "loadFile",
      "url": "/hotelx/reference/scalars/string",
      "description": "",
      "isDeprecated": true,
      "args": [
        {
          "typeString": "String!",
          "name": "input",
          "url": "/hotelx/reference/scalars/string",
          "description": ""
        }
      ],
      "deprecationReason": "",
      "descriptionSplitted": {
        "date": "2018-06-06",
        "first": "deprecated from",
        "second": ""
      },
      "deprecationDate": "2018-06-06"
    }
  ],
  "requireby": null,
  "enumValues": null,
  "operator": "type",
  "typename": "HotelXMutation",
  "hideGithubLink": true
}
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}
