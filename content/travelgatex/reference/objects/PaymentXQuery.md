{
  "title": "PaymentXQuery",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "ServiceStatus!",
      "name": "vaultStatusService",
      "url": "undefined/objects/servicestatus",
      "description": "Returns status of the search service.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "StoredCardConnection!",
      "name": "cards",
      "url": "undefined/objects/storedcardconnection",
      "description": "",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "PaymentXBookingInfoFilterInput!",
          "name": "bookingInfo",
          "url": "undefined/inputobjects/paymentxbookinginfofilterinput",
          "description": ""
        },
        {
          "typeString": "PaymentXBookingInfoCriteriaInput",
          "name": "bookingInfoCriteria",
          "url": "undefined/inputobjects/paymentxbookinginfocriteriainput",
          "description": ""
        }
      ]
    }
  ],
  "requireby": [
    {
      "name": "Query",
      "description": "The query root of TravelgateX's GraphQL interface.",
      "url": "undefined/schema/query"
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
