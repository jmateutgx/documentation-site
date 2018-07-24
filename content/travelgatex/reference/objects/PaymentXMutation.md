{
  "title": "PaymentXMutation",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "StoredCard!",
      "name": "storeCard",
      "url": "undefined/objects/storedcard",
      "description": "Store Card",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "PaymentXStoreCardInput!",
          "name": "input",
          "url": "undefined/inputobjects/paymentxstorecardinput",
          "description": ""
        }
      ]
    },
    {
      "typeString": "StoredCard!",
      "name": "deleteCard",
      "url": "undefined/objects/storedcard",
      "description": "Delete Card",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "PaymentXBookingInfoDeleteInput!",
          "name": "input",
          "url": "undefined/inputobjects/paymentxbookinginfodeleteinput",
          "description": ""
        }
      ]
    }
  ],
  "requireby": [
    {
      "name": "Mutation",
      "description": "The root query for implementing GraphQL mutations. Mutations are operations that change or update data on the server",
      "url": "undefined/schema/mutation"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "PaymentXMutation",
  "hideGithubLink": true
}
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
