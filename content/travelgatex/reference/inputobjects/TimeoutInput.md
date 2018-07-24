{
  "title": "TimeoutInput",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "Int!",
      "name": "search",
      "url": "undefined/scalars/int",
      "description": "Milliseconds before the search connection is closed.",
      "args": null
    },
    {
      "typeString": "Int!",
      "name": "quote",
      "url": "undefined/scalars/int",
      "description": "Milliseconds before the quote connection is closed.",
      "args": null
    },
    {
      "typeString": "Int!",
      "name": "book",
      "url": "undefined/scalars/int",
      "description": "Milliseconds before the book connection is closed.",
      "args": null
    }
  ],
  "requireby": [
    {
      "name": "DefaultSettingsInput",
      "description": "",
      "url": "undefined/inputobjects/defaultsettingsinput"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "TimeoutInput",
  "hideGithubLink": true
}
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
