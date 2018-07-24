{
  "title": "ServiceApi",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "ID!",
      "name": "code",
      "url": "undefined/scalars/id",
      "description": "Service API ID",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String!",
      "name": "name",
      "url": "undefined/scalars/string",
      "description": "Service API Name",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "[ServiceOperation]",
      "name": "operations",
      "url": "undefined/objects/serviceoperation",
      "description": "Operations that a Service Api has",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "[Error!]",
      "name": "error",
      "url": "undefined/objects/error",
      "description": "Errors",
      "isDeprecated": false,
      "args": null
    }
  ],
  "requireby": [
    {
      "name": "AdminQuery",
      "description": "The admin query root of TravelgateX's GraphQL interface.",
      "url": "undefined/objects/adminquery"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "ServiceApi",
  "hideGithubLink": true
}
Information related to a Service API
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
