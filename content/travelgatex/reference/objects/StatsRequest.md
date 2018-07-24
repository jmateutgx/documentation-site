{
  "title": "StatsRequest",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "Stat!",
      "name": "total",
      "url": "undefined/objects/stat",
      "description": "Total transaction time",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Stat!",
      "name": "validation",
      "url": "undefined/objects/stat",
      "description": "Request validation time",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Stat!",
      "name": "process",
      "url": "undefined/objects/stat",
      "description": "Process time. Contains communication time, parse time and plugin time.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Stat!",
      "name": "configuration",
      "url": "undefined/objects/stat",
      "description": "Build access time",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Stat!",
      "name": "request",
      "url": "undefined/objects/stat",
      "description": "Request time",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Stat!",
      "name": "response",
      "url": "undefined/objects/stat",
      "description": "Response time",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "StatPlugin",
      "name": "requestPlugin",
      "url": "undefined/objects/statplugin",
      "description": "Plugin execution time",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "StatPlugin",
      "name": "responsePlugin",
      "url": "undefined/objects/statplugin",
      "description": "Plugin execution time",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Int!",
      "name": "hotels",
      "url": "undefined/scalars/int",
      "description": "Number of hotels",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Int!",
      "name": "zones",
      "url": "undefined/scalars/int",
      "description": "Number of zones",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Int!",
      "name": "cities",
      "url": "undefined/scalars/int",
      "description": "Number of cities",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String!",
      "name": "dockerID",
      "url": "undefined/scalars/string",
      "description": "Docker Id",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "[StatAccess!]!",
      "name": "Accesses",
      "url": "undefined/objects/stataccess",
      "description": "Detail access time",
      "isDeprecated": false,
      "args": null
    }
  ],
  "requireby": [
    {
      "name": "HotelSearch",
      "description": "Results from Avail Hotel; contains all the available options for a given date and itinerary",
      "url": "undefined/objects/hotelsearch"
    },
    {
      "name": "Response",
      "description": "",
      "url": "undefined/interfaces/response"
    },
    {
      "name": "HotelQuote",
      "description": "",
      "url": "undefined/objects/hotelquote"
    },
    {
      "name": "HotelBooking",
      "description": "",
      "url": "undefined/objects/hotelbooking"
    },
    {
      "name": "HotelBookPayload",
      "description": "",
      "url": "undefined/objects/hotelbookpayload"
    },
    {
      "name": "HotelCancelPayload",
      "description": "",
      "url": "undefined/objects/hotelcancelpayload"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "StatsRequest",
  "hideGithubLink": true
}
Contains internal information.
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
