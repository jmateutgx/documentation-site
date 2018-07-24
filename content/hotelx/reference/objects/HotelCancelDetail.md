{
  "title": "HotelCancelDetail",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "Reference",
      "name": "reference",
      "url": "undefined/objects/reference",
      "description": "Booking ID in the Supplier's system",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String",
      "name": "cancelReference",
      "url": "undefined/scalars/string",
      "description": "Cancellation ID in the Supplier's system",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "BookStatusType",
      "name": "status",
      "url": "undefined/enums/bookstatustype",
      "description": "Booking Status.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Price",
      "name": "price",
      "url": "undefined/objects/price",
      "description": "Specifies the prices (Gross, Net and Amount) of the cancellation.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "HotelBookingDetail",
      "name": "booking",
      "url": "undefined/objects/hotelbookingdetail",
      "description": "Information about the booking.",
      "isDeprecated": false,
      "args": null
    }
  ],
  "requireby": [
    {
      "name": "HotelCancelPayload",
      "description": "",
      "url": "undefined/objects/hotelcancelpayload"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "HotelCancelDetail",
  "hideGithubLink": true
}
Contains information about cancel
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
