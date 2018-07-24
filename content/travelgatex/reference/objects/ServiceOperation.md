{
  "title": "ServiceOperation",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "ID!",
      "name": "code",
      "url": "undefined/scalars/id",
      "description": "Service Operation ID",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String!",
      "name": "name",
      "url": "undefined/scalars/string",
      "description": "Service Operation name",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String!",
      "name": "type",
      "url": "undefined/scalars/string",
      "description": "Service Operation type",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Int!",
      "name": "travelOperation",
      "url": "undefined/scalars/int",
      "description": "Service Operation Travel Operation ID (1: avail) (2: reservation) (3: batch) (4: batchLongRun)",
      "isDeprecated": false,
      "args": null
    }
  ],
  "requireby": [
    {
      "name": "ServiceApi",
      "description": "Information related to a Service API",
      "url": "undefined/objects/serviceapi"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "ServiceOperation",
  "hideGithubLink": true
}
Information related to an API operation
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
