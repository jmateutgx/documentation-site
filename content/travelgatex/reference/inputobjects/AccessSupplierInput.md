{
  "title": "AccessSupplierInput",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "String!",
      "name": "code",
      "url": "undefined/scalars/string",
      "description": "supplier code",
      "args": null
    },
    {
      "typeString": "String!",
      "name": "dll",
      "url": "undefined/scalars/string",
      "description": "supplier instance",
      "args": null
    },
    {
      "typeString": "Boolean!",
      "name": "isActive",
      "url": "undefined/scalars/boolean",
      "description": "Indicates if the supplier is active.",
      "args": null
    },
    {
      "typeString": "[SupplierGroupInput!]",
      "name": "groups",
      "url": "undefined/inputobjects/suppliergroupinput",
      "description": "groups related to this supplier",
      "args": null
    }
  ],
  "requireby": null,
  "enumValues": null,
  "operator": "type",
  "typename": "AccessSupplierInput",
  "hideGithubLink": true
}
Supplier input for data access management API
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}
