{
  "title": "Group",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "ID!",
      "name": "code",
      "url": "/stats/reference/scalars/id",
      "description": "",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "GroupData",
      "name": "groupData",
      "url": "/stats/reference/objects/groupdata",
      "description": "",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "[Error!]",
      "name": "error",
      "url": "/stats/reference/objects/error",
      "description": "Errors that abort services",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "DateTime!",
      "name": "createdAt",
      "url": "/stats/reference/scalars/datetime",
      "description": "Date created",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "DateTime!",
      "name": "updatedAt",
      "url": "/stats/reference/scalars/datetime",
      "description": "Date updated",
      "isDeprecated": false,
      "args": null
    }
  ],
  "requireby": [
    {
      "name": "GroupEdge",
      "description": "",
      "url": "/stats/reference/objects/groupedge"
    },
    {
      "name": "GroupData",
      "description": "",
      "url": "/stats/reference/objects/groupdata"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "Group",
  "hideGithubLink": true
}
Groups are organized hierarchically.
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
