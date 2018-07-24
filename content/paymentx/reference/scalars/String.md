{
  "title": "String",
  "description": "",
  "weight": 1,
  "fields": null,
  "requireby": [
    {
      "name": "ServiceStatus",
      "description": "Indicates the status of the service",
      "url": "undefined/objects/servicestatus"
    },
    {
      "name": "PaymentXBookingInfoFilterInput",
      "description": "",
      "url": "undefined/inputobjects/paymentxbookinginfofilterinput"
    },
    {
      "name": "StoredCardEdge",
      "description": "",
      "url": "undefined/objects/storedcardedge"
    },
    {
      "name": "PageInfo",
      "description": "",
      "url": "undefined/objects/pageinfo"
    },
    {
      "name": "AdviseMessage",
      "description": "List of advise messages.",
      "url": "undefined/interfaces/advisemessage"
    },
    {
      "name": "PaymentXBookingInfo",
      "description": "",
      "url": "undefined/objects/paymentxbookinginfo"
    },
    {
      "name": "PaymentCard",
      "description": "Input PaymentCard, if the payment is done by credit card, is it mandatory to specify the payment type and the credit card information",
      "url": "undefined/objects/paymentcard"
    },
    {
      "name": "PointOfSaleData",
      "description": "",
      "url": "undefined/objects/pointofsaledata"
    },
    {
      "name": "Holder",
      "description": "Holder object that contains the occupant's (pax's) name and surname.",
      "url": "undefined/objects/holder"
    },
    {
      "name": "ExternalMessage",
      "description": "",
      "url": "undefined/objects/externalmessage"
    },
    {
      "name": "PaymentXBookingInfoDeleteInput",
      "description": "",
      "url": "undefined/inputobjects/paymentxbookinginfodeleteinput"
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
