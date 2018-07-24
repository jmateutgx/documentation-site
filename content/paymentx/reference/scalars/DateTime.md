{
  "title": "DateTime",
  "description": "",
  "weight": 1,
  "fields": null,
  "requireby": [
    {
      "name": "PaymentXBookingInfoFilterInput",
      "description": "",
      "url": "/paymentx/reference/inputobjects/paymentxbookinginfofilterinput"
    },
    {
      "name": "StoredCard",
      "description": "",
      "url": "/paymentx/reference/objects/storedcard"
    },
    {
      "name": "PointOfSale",
      "description": "",
      "url": "/paymentx/reference/objects/pointofsale"
    },
    {
      "name": "StoredCard",
      "description": "",
      "url": "/paymentx/reference/objects/storedcard"
    },
    {
      "name": "PointOfSale",
      "description": "",
      "url": "/paymentx/reference/objects/pointofsale"
    }
  ],
  "enumValues": null,
  "operator": "scalar",
  "typename": "DateTime",
  "hideGithubLink": true
}
The DateTime type represents DateTime values. A good example might be a transaction TimeSpan.
In queries or mutations, DateTime fields have to be specified in ISO 8601 format with enclosing double quotes: "2017-10-22T13:57:31.123Z".
## GraphQL schema definition

{{% graphql-schema-scalar %}}

## Required by

{{% graphql-require-by %}}
