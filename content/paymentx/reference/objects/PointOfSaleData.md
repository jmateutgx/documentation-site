{
  "title": "PointOfSaleData",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "ID!",
      "name": "code",
      "url": "undefined/scalars/id",
      "description": "POS Identifier",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String",
      "name": "name",
      "url": "undefined/scalars/string",
      "description": "POS Name",
      "isDeprecated": false,
      "args": null
    }
  ],
  "requireby": [
    {
      "name": "PointOfSale",
      "description": "",
      "url": "undefined/objects/pointofsale"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "PointOfSaleData",
  "hideGithubLink": true
}
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
