{
  "title": "Currency",
  "description": "",
  "weight": 1,
  "fields": null,
  "requireby": [
    {
      "name": "CriteriaSearch",
      "description": "Search criteria contains destination, travel dates and the number of pax in each room.",
      "url": "/hotelx/reference/objects/criteriasearch"
    },
    {
      "name": "Price",
      "description": "Price indicates the value of the room/option.\nSupplements and/or surcharges can be included into the price, and will be verified with nodes Supplements/Surcharges.",
      "url": "/hotelx/reference/objects/price"
    },
    {
      "name": "Exchange",
      "description": "Provides information about the currency of original, and its rate applied over the results returned by the Supplier.",
      "url": "/hotelx/reference/objects/exchange"
    },
    {
      "name": "Markup",
      "description": "Informs markup applied over supplier price.",
      "url": "/hotelx/reference/objects/markup"
    },
    {
      "name": "CancelPenalty",
      "description": "Contains information for cancellation penalities..",
      "url": "/hotelx/reference/objects/cancelpenalty"
    }
  ],
  "enumValues": null,
  "operator": "scalar",
  "typename": "Currency",
  "hideGithubLink": true
}
The Currenty type represents Currency values. A good example might be a Rate Price Currency.
In queries or mutations, Currency fields have to be specified in ISO 4217 format with enclosing double quotes "EUR".
## GraphQL schema definition

{{% graphql-schema-scalar %}}

## Required by

{{% graphql-require-by %}}
