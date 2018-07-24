{
  "title": "CancelPenalty",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "Int!",
      "name": "hoursBefore",
      "url": "undefined/scalars/int",
      "description": "Cancellation fees applicable X number of hours before the check-in date",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "CancelPenaltyType!",
      "name": "penaltyType",
      "url": "undefined/enums/cancelpenaltytype",
      "description": "Type of penalty; this can be Nights, Percent or Import",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Currency!",
      "name": "currency",
      "url": "undefined/scalars/currency",
      "description": "Currency used in the cancellation policy",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Float!",
      "name": "value",
      "url": "undefined/scalars/float",
      "description": "Value of the cancellation policy",
      "isDeprecated": false,
      "args": null
    }
  ],
  "requireby": null,
  "enumValues": null,
  "operator": "type",
  "typename": "CancelPenalty",
  "hideGithubLink": true
}
Contains information for cancellation penalities..
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}
