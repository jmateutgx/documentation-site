{
  "title": "PaymentXQuery",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "ServiceStatus!",
      "name": "vaultStatusService",
      "url": "/paymentx/reference/objects/servicestatus",
      "description": "Returns status of the search service.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "StoredCardConnection!",
      "name": "cards",
      "url": "/paymentx/reference/objects/storedcardconnection",
      "description": "",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "PaymentXBookingInfoFilterInput!",
          "name": "bookingInfo",
          "url": "/paymentx/reference/inputobjects/paymentxbookinginfofilterinput",
          "description": ""
        },
        {
          "typeString": "PaymentXBookingInfoCriteriaInput",
          "name": "bookingInfoCriteria",
          "url": "/paymentx/reference/inputobjects/paymentxbookinginfocriteriainput",
          "description": ""
        }
      ]
    }
  ],
  "requireby": null,
  "enumValues": null,
  "operator": "type",
  "typename": "PaymentXQuery",
  "hideGithubLink": true
}
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}
