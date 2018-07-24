{
  "title": "ID",
  "description": "",
  "weight": 1,
  "fields": null,
  "requireby": [
    {
      "name": "PaymentXBookingInfoFilterInput",
      "description": "",
      "url": "undefined/inputobjects/paymentxbookinginfofilterinput"
    },
    {
      "name": "StoredCard",
      "description": "",
      "url": "undefined/objects/storedcard"
    },
    {
      "name": "AdviseMessage",
      "description": "List of advise messages.",
      "url": "undefined/interfaces/advisemessage"
    },
    {
      "name": "PointOfSale",
      "description": "",
      "url": "undefined/objects/pointofsale"
    },
    {
      "name": "PointOfSaleData",
      "description": "",
      "url": "undefined/objects/pointofsaledata"
    },
    {
      "name": "PaymentXBookingInfoDeleteInput",
      "description": "",
      "url": "undefined/inputobjects/paymentxbookinginfodeleteinput"
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
