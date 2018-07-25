{
  "title": "PaymentXQuery",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "ServiceStatus!",
      "name": "vaultStatusService",
      "url": "/travelgatex/reference/objects/servicestatus",
      "description": "Returns status of the search service.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "StoredCardConnection!",
      "name": "cards",
      "url": "/travelgatex/reference/objects/storedcardconnection",
      "description": "",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "PaymentXBookingInfoFilterInput!",
          "name": "bookingInfo",
          "url": "/travelgatex/reference/inputobjects/paymentxbookinginfofilterinput",
          "description": ""
        },
        {
          "typeString": "PaymentXBookingInfoCriteriaInput",
          "name": "bookingInfoCriteria",
          "url": "/travelgatex/reference/inputobjects/paymentxbookinginfocriteriainput",
          "description": ""
        }
      ]
    }
  ],
  "requireby": [
    {
      "name": "Query",
      "description": "The query root of TravelgateX's GraphQL interface.",
      "url": "/travelgatex/reference/schema/query"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "PaymentXQuery",
  "hideGithubLink": true
}
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
