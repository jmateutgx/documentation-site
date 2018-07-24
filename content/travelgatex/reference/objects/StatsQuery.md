{
  "title": "StatsQuery",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "StatsConnection!",
      "name": "report",
      "url": "undefined/objects/statsconnection",
      "description": "The report query, represents all of the entry points into our object graph",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "StatsFilterInput!",
          "name": "filter",
          "url": "undefined/inputobjects/statsfilterinput",
          "description": ""
        },
        {
          "typeString": "Int",
          "name": "first",
          "url": "undefined/scalars/int",
          "description": ""
        },
        {
          "typeString": "Int",
          "name": "last",
          "url": "undefined/scalars/int",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "before",
          "url": "undefined/scalars/string",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "after",
          "url": "undefined/scalars/string",
          "description": ""
        }
      ]
    }
  ],
  "requireby": [
    {
      "name": "Query",
      "description": "The query root of TravelgateX's GraphQL interface.",
      "url": "undefined/schema/query"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "StatsQuery",
  "hideGithubLink": true
}
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
