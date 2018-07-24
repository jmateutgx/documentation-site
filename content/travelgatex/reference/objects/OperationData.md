{
  "title": "OperationData",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "ID!",
      "name": "id",
      "url": "undefined/scalars/id",
      "description": "",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "ID!",
      "name": "code",
      "url": "undefined/scalars/id",
      "description": "",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String",
      "name": "label",
      "url": "undefined/scalars/string",
      "description": "",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "[OperationType!]!",
      "name": "types",
      "url": "undefined/enums/operationtype",
      "description": "",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "API",
      "name": "api",
      "url": "undefined/objects/api",
      "description": "",
      "isDeprecated": false,
      "args": null
    }
  ],
  "requireby": [
    {
      "name": "Operation",
      "description": "",
      "url": "undefined/objects/operation"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "OperationData",
  "hideGithubLink": true
}
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
