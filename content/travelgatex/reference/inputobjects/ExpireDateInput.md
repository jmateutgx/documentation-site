{
  "title": "ExpireDateInput",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "Int!",
      "name": "month",
      "url": "undefined/scalars/int",
      "description": "Month MM",
      "args": null
    },
    {
      "typeString": "Int!",
      "name": "year",
      "url": "undefined/scalars/int",
      "description": "Year yy",
      "args": null
    }
  ],
  "requireby": [
    {
      "name": "PaymentCardInput",
      "description": "Input PaymentCard, if the payment is done by credit card, is it mandatory to specify the payment type and the credit card information",
      "url": "undefined/inputobjects/paymentcardinput"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "ExpireDateInput",
  "hideGithubLink": true
}
The card expiration date
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
