{
  "title": "HotelBooking",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "StatsRequest",
      "name": "stats",
      "url": "undefined/objects/statsrequest",
      "description": "Application stats in string format",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "String!",
          "name": "token",
          "url": "undefined/scalars/string",
          "description": ""
        }
      ]
    },
    {
      "typeString": "AuditData",
      "name": "auditData",
      "url": "undefined/objects/auditdata",
      "description": "Data sent and received in the supplier's native format.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "[HotelBookingDetail!]",
      "name": "bookings",
      "url": "undefined/objects/hotelbookingdetail",
      "description": "Details about booking",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "[Error!]",
      "name": "errors",
      "url": "undefined/objects/error",
      "description": "Errors that abort services",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "[Warning!]",
      "name": "warnings",
      "url": "undefined/objects/warning",
      "description": "Potentially harmful situations or errors, but ones that will not forcibly abort the service",
      "isDeprecated": false,
      "args": null
    }
  ],
  "requireby": [
    {
      "name": "HotelXQuery",
      "description": "",
      "url": "undefined/objects/hotelxquery"
    },
    {
      "name": "Booking",
      "description": "Returns detailed information about books.",
      "url": "undefined/objects/booking"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "HotelBooking",
  "hideGithubLink": true
}
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
