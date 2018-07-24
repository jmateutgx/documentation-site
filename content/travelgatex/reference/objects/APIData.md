{
  "title": "APIData",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "ID!",
      "name": "code",
      "url": "undefined/scalars/id",
      "description": "API Code",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "ID!",
      "name": "id",
      "url": "undefined/scalars/id",
      "description": "API ID",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Boolean!",
      "name": "isEditable",
      "url": "undefined/scalars/boolean",
      "description": "Is API Editable or not.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String",
      "name": "label",
      "url": "undefined/scalars/string",
      "description": "API label",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "GroupConnection",
      "name": "groups",
      "url": "undefined/objects/groupconnection",
      "description": "which groups are asigned this API?",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "[ID!]",
          "name": "codes",
          "url": "undefined/scalars/id",
          "description": ""
        },
        {
          "typeString": "GroupType",
          "name": "type",
          "url": "undefined/enums/grouptype",
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
    },
    {
      "typeString": "ResourceConnection",
      "name": "resources",
      "url": "undefined/objects/resourceconnection",
      "description": "which resources are asigned this API?",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "[ID!]",
          "name": "codes",
          "url": "undefined/scalars/id",
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
    },
    {
      "typeString": "OperationConnection",
      "name": "operations",
      "url": "undefined/objects/operationconnection",
      "description": "which operations are asigned this API?",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "[ID!]",
          "name": "codes",
          "url": "undefined/scalars/id",
          "description": ""
        },
        {
          "typeString": "OperationType",
          "name": "type",
          "url": "undefined/enums/operationtype",
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
      "name": "API",
      "description": "",
      "url": "undefined/objects/api"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "APIData",
  "hideGithubLink": true
}
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
