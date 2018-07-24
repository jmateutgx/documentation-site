{
  "title": "ID",
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
      "name": "AdviseMessage",
      "description": "List of advise messages.",
      "url": "/paymentx/reference/interfaces/advisemessage"
    },
    {
      "name": "PointOfSale",
      "description": "",
      "url": "/paymentx/reference/objects/pointofsale"
    },
    {
      "name": "PointOfSaleData",
      "description": "",
      "url": "/paymentx/reference/objects/pointofsaledata"
    },
    {
      "name": "StoredCard",
      "description": "",
      "url": "/paymentx/reference/objects/storedcard"
    },
    {
      "name": "PaymentXBookingInfoDeleteInput",
      "description": "",
      "url": "/paymentx/reference/inputobjects/paymentxbookinginfodeleteinput"
    },
    {
      "name": "PointOfSale",
      "description": "",
      "url": "/paymentx/reference/objects/pointofsale"
    },
    {
      "name": "PointOfSaleData",
      "description": "",
      "url": "/paymentx/reference/objects/pointofsaledata"
    }
  ],
  "enumValues": null,
  "operator": "scalar",
  "typename": "ID",
  "hideGithubLink": true
}
The `ID` scalar type represents a unique identifier, often used to refetch an object or as key for a cache. The ID type appears in a JSON response as a String; however, it is not intended to be human-readable. When expected as an input type, any string (such as `"4"`) or integer (such as `4`) input value will be accepted as an ID.
## GraphQL schema definition

{{% graphql-schema-scalar %}}

## Required by

{{% graphql-require-by %}}
