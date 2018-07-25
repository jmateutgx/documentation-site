{
  "title": "PageInfo",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "Boolean!",
      "name": "hasNextPage",
      "url": "/stats/reference/scalars/boolean",
      "description": "",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Boolean!",
      "name": "hasPreviousPage",
      "url": "/stats/reference/scalars/boolean",
      "description": "",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String!",
      "name": "startCursor",
      "url": "/stats/reference/scalars/string",
      "description": "",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String!",
      "name": "endCursor",
      "url": "/stats/reference/scalars/string",
      "description": "",
      "isDeprecated": false,
      "args": null
    }
  ],
  "requireby": [
    {
      "name": "StatsConnection",
      "description": "",
      "url": "/stats/reference/objects/statsconnection"
    },
    {
      "name": "AccessConnection",
      "description": "",
      "url": "/stats/reference/objects/accessconnection"
    },
    {
      "name": "GroupConnection",
      "description": "",
      "url": "/stats/reference/objects/groupconnection"
    },
    {
      "name": "ResourceConnection",
      "description": "",
      "url": "/stats/reference/objects/resourceconnection"
    },
    {
      "name": "OperationConnection",
      "description": "",
      "url": "/stats/reference/objects/operationconnection"
    },
    {
      "name": "MemberConnection",
      "description": "",
      "url": "/stats/reference/objects/memberconnection"
    },
    {
      "name": "APIConnection",
      "description": "",
      "url": "/stats/reference/objects/apiconnection"
    },
    {
      "name": "SupplierConnection",
      "description": "",
      "url": "/stats/reference/objects/supplierconnection"
    },
    {
      "name": "ClientConnection",
      "description": "",
      "url": "/stats/reference/objects/clientconnection"
    },
    {
      "name": "RoleConnection",
      "description": "",
      "url": "/stats/reference/objects/roleconnection"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "PageInfo",
  "hideGithubLink": true
}
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
