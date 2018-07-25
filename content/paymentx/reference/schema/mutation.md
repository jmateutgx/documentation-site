{
  "title": "PaymentXMutation",
  "description": "",
  "weight": 2,
  "fields": [
    {
      "typeString": "StoredCard!",
      "name": "storeCard",
      "url": "/paymentx/reference/objects/storedcard",
      "description": "Store Card",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "PaymentXStoreCardInput!",
          "name": "input",
          "url": "/paymentx/reference/inputobjects/paymentxstorecardinput",
          "description": ""
        }
      ]
    },
    {
      "typeString": "StoredCard!",
      "name": "deleteCard",
      "url": "/paymentx/reference/objects/storedcard",
      "description": "Delete Card",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "PaymentXBookingInfoDeleteInput!",
          "name": "input",
          "url": "/paymentx/reference/inputobjects/paymentxbookinginfodeleteinput",
          "description": ""
        }
      ]
    }
  ],
  "requireby": null,
  "enumValues": null,
  "operator": "type",
  "typename": "PaymentXMutation",
  "hideGithubLink": true
}
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}
