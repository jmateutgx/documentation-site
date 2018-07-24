{
  "title": "Access",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "ID!",
      "name": "code",
      "url": "undefined/scalars/id",
      "description": "",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "AccessData",
      "name": "accessData",
      "url": "undefined/objects/accessdata",
      "description": "",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "[Error!]",
      "name": "error",
      "url": "undefined/objects/error",
      "description": "Errors that abort services",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "DateTime!",
      "name": "createdAt",
      "url": "undefined/scalars/datetime",
      "description": "Date created",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "DateTime!",
      "name": "updatedAt",
      "url": "undefined/scalars/datetime",
      "description": "Date updated",
      "isDeprecated": false,
      "args": null
    }
  ],
  "requireby": [
    {
      "name": "StatsData",
      "description": "",
      "url": "undefined/objects/statsdata"
    },
    {
      "name": "AccessData",
      "description": "",
      "url": "undefined/objects/accessdata"
    },
    {
      "name": "AccessEdge",
      "description": "",
      "url": "undefined/objects/accessedge"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "Access",
  "hideGithubLink": true
}
An Access is a set of credentials and configuration in order to access the system of a Supplier.
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
