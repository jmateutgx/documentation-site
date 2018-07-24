{
  "title": "Stat",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "DateTime!",
      "name": "start",
      "url": "undefined/scalars/datetime",
      "description": "Start UTC",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "DateTime!",
      "name": "end",
      "url": "undefined/scalars/datetime",
      "description": "End UTC",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Float",
      "name": "duration",
      "url": "undefined/scalars/float",
      "description": "Difference between start and end in miliseconds",
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
      "name": "StatPlugin",
      "description": "",
      "url": "undefined/objects/statplugin"
    },
    {
      "name": "StatAccess",
      "description": "",
      "url": "undefined/objects/stataccess"
    },
    {
      "name": "StatTransaction",
      "description": "",
      "url": "undefined/objects/stattransaction"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "Stat",
  "hideGithubLink": true
}
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
