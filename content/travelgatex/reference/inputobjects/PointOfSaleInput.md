{
  "title": "PointOfSaleInput",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "ID!",
      "name": "code",
      "url": "undefined/scalars/id",
      "description": "POS Identifier",
      "args": null
    },
    {
      "typeString": "String!",
      "name": "name",
      "url": "undefined/scalars/string",
      "description": "POS Name",
      "args": null
    }
  ],
  "requireby": [
    {
      "name": "PaymentXBookingInfoInput",
      "description": "",
      "url": "undefined/inputobjects/paymentxbookinginfoinput"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "PointOfSaleInput",
  "hideGithubLink": true
}
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
