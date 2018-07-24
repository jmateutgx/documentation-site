{
  "title": "OperationDetailed",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "Operation!",
      "name": "operation",
      "url": "undefined/objects/operation",
      "description": "Operation information",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Int!",
      "name": "totalHits",
      "url": "undefined/scalars/int",
      "description": "Total hits.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "[StatsInfo!]",
      "name": "detailedHits",
      "url": "undefined/objects/statsinfo",
      "description": "Hits grouped depending on their status",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "[StatsInfoTypes!]",
          "name": "type",
          "url": "undefined/enums/statsinfotypes",
          "description": ""
        },
        {
          "typeString": "[Int!]",
          "name": "code",
          "url": "undefined/scalars/int",
          "description": ""
        }
      ]
    },
    {
      "typeString": "Boolean!",
      "name": "cache",
      "url": "undefined/scalars/boolean",
      "description": "Responsible for the execution of the this stats. If TRUE then cache, else client",
      "isDeprecated": false,
      "args": null
    }
  ],
  "requireby": null,
  "enumValues": null,
  "operator": "type",
  "typename": "OperationDetailed",
  "hideGithubLink": true
}
Stats information per operation
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}
