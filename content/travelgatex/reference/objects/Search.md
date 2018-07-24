{
  "title": "Search",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "HotelSearch",
      "name": "hotel",
      "url": "undefined/objects/hotelsearch",
      "description": "Available options of an hotel for a given date and itinerary. It does not filter different classes, times or\nfares. It will always retrieve all results returned by the suppliers. The availability request is very straight\nforward. It only requires the criteria of search (destination, travel dates and the number of pax in each room).\nBut you must preload the other fields in our system by complete the fields absents.",
      "isDeprecated": true,
      "args": [
        {
          "typeString": "String",
          "name": "token",
          "url": "undefined/scalars/string",
          "description": ""
        },
        {
          "typeString": "HotelCriteriaSearchInput",
          "name": "criteria",
          "url": "undefined/inputobjects/hotelcriteriasearchinput",
          "description": ""
        },
        {
          "typeString": "HotelSettingsInput",
          "name": "settings",
          "url": "undefined/inputobjects/hotelsettingsinput",
          "description": ""
        },
        {
          "typeString": "FilterInput",
          "name": "filter",
          "url": "undefined/inputobjects/filterinput",
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
      "typeName": "Search"
    }
  ],
  "requireby": null,
  "enumValues": null,
  "operator": "type",
  "typename": "Search",
  "hideGithubLink": true
}
Available options for a given date and itinerary. It does not filter different classes, times or
fares. It will always retrieve all results returned by the suppliers. The availability request is very straight
forward.
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}
