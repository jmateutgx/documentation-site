{
  "title": "AuditData",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "[Transactions!]!",
      "name": "transactions",
      "url": "undefined/objects/transactions",
      "description": "List of transactions data",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "DateTime!",
      "name": "timeStamp",
      "url": "undefined/scalars/datetime",
      "description": "TimeStamp",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Float!",
      "name": "processTime",
      "url": "undefined/scalars/float",
      "description": "Process time in milliseconds (ms)",
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
  "typename": "AuditData",
  "hideGithubLink": true
}
Data sent and received in the supplier’s native format.
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
