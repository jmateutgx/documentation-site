{
  "title": "Float",
  "description": "",
  "weight": 1,
  "fields": null,
  "requireby": [
    {
      "name": "Coordinates",
      "description": "Geographical coordinates corresponding to a location.",
      "url": "undefined/objects/coordinates"
    },
    {
      "name": "AuditData",
      "description": "Data sent and received in the supplier’s native format.",
      "url": "undefined/objects/auditdata"
    },
    {
      "name": "Stat",
      "description": "",
      "url": "undefined/objects/stat"
    },
    {
      "name": "Price",
      "description": "Price indicates the value of the room/option.\nSupplements and/or surcharges can be included into the price, and will be verified with nodes Supplements/Surcharges.",
      "url": "undefined/objects/price"
    },
    {
      "name": "Exchange",
      "description": "Provides information about the currency of original, and its rate applied over the results returned by the Supplier.",
      "url": "undefined/objects/exchange"
    },
    {
      "name": "Markup",
      "description": "Informs markup applied over supplier price.",
      "url": "undefined/objects/markup"
    },
    {
      "name": "Rule",
      "description": "",
      "url": "undefined/objects/rule"
    },
    {
      "name": "CancelPenalty",
      "description": "Contains information for cancellation penalities..",
      "url": "undefined/objects/cancelpenalty"
    }
  ],
  "enumValues": null,
  "operator": "scalar",
  "typename": "Float",
  "hideGithubLink": true
}
The `Float` scalar type represents signed double-precision fractional values as specified by [IEEE 754](http://en.wikipedia.org/wiki/IEEE_floating_point). 
## GraphQL schema definition

{{% graphql-schema-scalar %}}

## Required by

{{% graphql-require-by %}}
