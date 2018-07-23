{
  "title": "String",
  "description": "",
  "weight": 1,
  "fields": null,
  "requireby": [
    {
      "name": "ServiceStatus",
      "description": "Indicates the status of the service",
      "url": "/paymentx/reference/objects/servicestatus"
    },
    {
      "name": "StoredCardEdge",
      "description": "",
      "url": "/paymentx/reference/objects/storedcardedge"
    },
    {
      "name": "PageInfo",
      "description": "",
      "url": "/paymentx/reference/objects/pageinfo"
    },
    {
      "name": "AdviseMessage",
      "description": "",
      "url": "/paymentx/reference/interfaces/advisemessage"
    },
    {
      "name": "PaymentXBookingInfo",
      "description": "",
      "url": "/paymentx/reference/objects/paymentxbookinginfo"
    },
    {
      "name": "PaymentCard",
      "description": "Input PaymentCard, if the payment is done by credit card, is it mandatory to specify the payment type and the credit card information",
      "url": "/paymentx/reference/objects/paymentcard"
    },
    {
      "name": "PointOfSaleData",
      "description": "",
      "url": "/paymentx/reference/objects/pointofsaledata"
    },
    {
      "name": "Holder",
      "description": "Holder object that contains the occupant's (pax's) name and surname.",
      "url": "/paymentx/reference/objects/holder"
    },
    {
      "name": "ExternalMessage",
      "description": "",
      "url": "/paymentx/reference/objects/externalmessage"
    }
  ],
  "enumValues": null,
  "operator": "scalar",
  "typename": "String",
  "hideGithubLink": true
}
The `String` scalar type represents textual data, represented as UTF-8 character sequences. The String type is most often used by GraphQL to represent free-form human-readable text.
## GraphQL schema definition

{{% graphql-schema-scalar %}}

## Required by

{{% graphql-require-by %}}
