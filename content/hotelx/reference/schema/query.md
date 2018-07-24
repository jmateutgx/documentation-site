{
  "title": "HotelXQuery",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "BoardConnection!",
      "name": "boards",
      "url": "undefined/objects/boardconnection",
      "description": "Query to obtain Boards",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "HotelXBoardQueryInput!",
          "name": "criteria",
          "url": "undefined/inputobjects/hotelxboardqueryinput",
          "description": ""
        },
        {
          "typeString": "RelayInput!",
          "name": "relay",
          "url": "undefined/inputobjects/relayinput",
          "description": ""
        }
      ]
    },
    {
      "typeString": "CategoryConnection!",
      "name": "categories",
      "url": "undefined/objects/categoryconnection",
      "description": "Query to obtain Categories",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "HotelXCategoryQueryInput!",
          "name": "criteria",
          "url": "undefined/inputobjects/hotelxcategoryqueryinput",
          "description": ""
        },
        {
          "typeString": "RelayInput!",
          "name": "relay",
          "url": "undefined/inputobjects/relayinput",
          "description": ""
        }
      ]
    },
    {
      "typeString": "HotelConnection!",
      "name": "hotels",
      "url": "undefined/objects/hotelconnection",
      "description": "Query to obtain Hotels",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "HotelXHotelListInput!",
          "name": "criteria",
          "url": "undefined/inputobjects/hotelxhotellistinput",
          "description": ""
        },
        {
          "typeString": "RelayInput!",
          "name": "relay",
          "url": "undefined/inputobjects/relayinput",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "token",
          "url": "undefined/scalars/string",
          "description": ""
        },
        {
          "typeString": "HotelXHotelFilterInput",
          "name": "filter",
          "url": "undefined/inputobjects/hotelxhotelfilterinput",
          "description": ""
        }
      ]
    },
    {
      "typeString": "RoomConnection!",
      "name": "rooms",
      "url": "undefined/objects/roomconnection",
      "description": "Query to obtain rooms",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "HotelXRoomQueryInput!",
          "name": "criteria",
          "url": "undefined/inputobjects/hotelxroomqueryinput",
          "description": ""
        },
        {
          "typeString": "RelayInput!",
          "name": "relay",
          "url": "undefined/inputobjects/relayinput",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "token",
          "url": "undefined/scalars/string",
          "description": ""
        }
      ]
    },
    {
      "typeString": "DestinationConnection!",
      "name": "destinations",
      "url": "undefined/objects/destinationconnection",
      "description": "Query to obtain Destinations",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "HotelXDestinationListInput!",
          "name": "criteria",
          "url": "undefined/inputobjects/hotelxdestinationlistinput",
          "description": ""
        },
        {
          "typeString": "RelayInput!",
          "name": "relay",
          "url": "undefined/inputobjects/relayinput",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "token",
          "url": "undefined/scalars/string",
          "description": ""
        }
      ]
    },
    {
      "typeString": "[DestinationSearchResult]!",
      "name": "destinationSearcher",
      "url": "#",
      "description": "Returns hotels and destinations that contains the indicated text.",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "HotelXDestinationSearcherInput!",
          "name": "criteria",
          "url": "undefined/inputobjects/hotelxdestinationsearcherinput",
          "description": ""
        }
      ]
    },
    {
      "typeString": "HotelSearch",
      "name": "search",
      "url": "undefined/objects/hotelsearch",
      "description": "Available options of an hotel for a given date and itinerary. It does not filter different classes, times or\nfares. It will always retrieve all results returned by the suppliers. The availability request is very straight\nforward. It only requires the criteria of search (destination, travel dates and the number of pax in each room).\nBut you must preload the other fields in our system by complete the fields absents.",
      "isDeprecated": false,
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
      ]
    },
    {
      "typeString": "HotelQuote",
      "name": "quote",
      "url": "undefined/objects/hotelquote",
      "description": "Returns the total price and cancellation policies of the Option selected in the previous step (Search).",
      "isDeprecated": false,
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
      ]
    },
    {
      "typeString": "HotelBooking",
      "name": "booking",
      "url": "undefined/objects/hotelbooking",
      "description": "Returns detailed information about books, you can indicated a list of locators or a range date.",
      "isDeprecated": false,
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
      ]
    },
    {
      "typeString": "ServiceStatus!",
      "name": "searchStatusService",
      "url": "undefined/objects/servicestatus",
      "description": "Returns status of the search service.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "ServiceStatus!",
      "name": "quoteStatusService",
      "url": "undefined/objects/servicestatus",
      "description": "Returns status of the quote service.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "ServiceStatus!",
      "name": "bookStatusService",
      "url": "undefined/objects/servicestatus",
      "description": "Returns status of the new booking service.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "ServiceStatus!",
      "name": "cancelStatusService",
      "url": "undefined/objects/servicestatus",
      "description": "Returns status of the cancellation service.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "ServiceStatus!",
      "name": "bookingStatusService",
      "url": "undefined/objects/servicestatus",
      "description": "Returns status of the booking service.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Mapping!",
      "name": "mapping",
      "url": "undefined/objects/mapping",
      "description": "Returns map codes of a group. You can get hotel map, room map, and board map.",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "String!",
          "name": "groupCode",
          "url": "undefined/scalars/string",
          "description": ""
        }
      ]
    }
  ],
  "requireby": null,
  "enumValues": null,
  "operator": "type",
  "typename": "HotelXQuery",
  "hideGithubLink": true
}
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}
