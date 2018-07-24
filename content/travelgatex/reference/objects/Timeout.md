{
  "title": "Timeout",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "Int!",
      "name": "search",
      "url": "undefined/scalars/int",
      "description": "Milliseconds before the search connection is closed.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Int!",
      "name": "quote",
      "url": "undefined/scalars/int",
      "description": "Milliseconds before the quote connection is closed.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Int!",
      "name": "book",
      "url": "undefined/scalars/int",
      "description": "Milliseconds before the book connection is closed.",
      "isDeprecated": false,
      "args": null
    }
  ],
  "requireby": [
    {
      "name": "DefaultSettings",
      "description": "",
      "url": "undefined/objects/defaultsettings"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "Timeout",
  "hideGithubLink": true
}
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
