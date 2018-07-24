{
  "title": "PaymentXBookingInfo",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "String!",
      "name": "organization",
      "url": "undefined/scalars/string",
      "description": "Responsible organization of the booked property.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "PointOfSale!",
      "name": "pointOfSale",
      "url": "undefined/objects/pointofsale",
      "description": "",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String!",
      "name": "bookingReference",
      "url": "undefined/scalars/string",
      "description": "Indicates the referece of the booking",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Date!",
      "name": "checkOut",
      "url": "undefined/scalars/date",
      "description": "Check-out, booking date Format: YYYY-MM-DD",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Date!",
      "name": "checkIn",
      "url": "undefined/scalars/date",
      "description": "Check-in, booking date Format: YYYY-MM-DD",
      "isDeprecated": false,
      "args": null
    }
  ],
  "requireby": [
    {
      "name": "StoredCardData",
      "description": "",
      "url": "undefined/objects/storedcarddata"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "PaymentXBookingInfo",
  "hideGithubLink": true
}
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
