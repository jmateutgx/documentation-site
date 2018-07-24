{
  "title": "StatPlugin",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "String!",
      "name": "name",
      "url": "undefined/scalars/string",
      "description": "Plugin name",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Stat!",
      "name": "total",
      "url": "undefined/objects/stat",
      "description": "total plugin time",
      "isDeprecated": false,
      "args": null
    }
  ],
  "requireby": [
    {
      "name": "StatsRequest",
      "description": "Contains internal information.",
      "url": "undefined/objects/statsrequest"
    },
    {
      "name": "StatAccess",
      "description": "",
      "url": "undefined/objects/stataccess"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "StatPlugin",
  "hideGithubLink": true
}
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
