{
  "title": "StatTransaction",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "String!",
      "name": "reference",
      "url": "undefined/scalars/string",
      "description": "Extra information about transaction.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Stat!",
      "name": "total",
      "url": "undefined/objects/stat",
      "description": "Total transaction time",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Stat!",
      "name": "buildRequest",
      "url": "undefined/objects/stat",
      "description": "Build request time",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Stat!",
      "name": "workerCommunication",
      "url": "undefined/objects/stat",
      "description": "Worker connection time",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Stat!",
      "name": "parseResponse",
      "url": "undefined/objects/stat",
      "description": "Parse response time",
      "isDeprecated": false,
      "args": null
    }
  ],
  "requireby": null,
  "enumValues": null,
  "operator": "type",
  "typename": "StatTransaction",
  "hideGithubLink": true
}
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}
