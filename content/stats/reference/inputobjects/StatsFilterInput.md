{
  "title": "StatsFilterInput",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "[ID!]",
      "name": "groups",
      "url": "undefined/scalars/id",
      "description": "Groups codes list",
      "args": null
    },
    {
      "typeString": "[ID!]",
      "name": "accesses",
      "url": "undefined/scalars/id",
      "description": "List of accesses",
      "args": null
    },
    {
      "typeString": "[ID!]",
      "name": "suppliers",
      "url": "undefined/scalars/id",
      "description": "List of suppliers",
      "args": null
    },
    {
      "typeString": "[ServiceApiType!]",
      "name": "serviceApis",
      "url": "undefined/enums/serviceapitype",
      "description": "List of services apis",
      "args": null
    },
    {
      "typeString": "[ServiceOperationType!]",
      "name": "operation",
      "url": "undefined/enums/serviceoperationtype",
      "description": "List of services operations",
      "args": null
    },
    {
      "typeString": "[ID!]",
      "name": "serviceOperations",
      "url": "undefined/scalars/id",
      "description": "",
      "args": null
    },
    {
      "typeString": "DateTime!",
      "name": "from",
      "url": "undefined/scalars/datetime",
      "description": "From date of search",
      "args": null
    },
    {
      "typeString": "DateTime!",
      "name": "to",
      "url": "undefined/scalars/datetime",
      "description": "To date of search",
      "args": null
    }
  ],
  "requireby": null,
  "enumValues": null,
  "operator": "type",
  "typename": "StatsFilterInput",
  "hideGithubLink": true
}
Filters needed to do a search.
Users (List of users), Suppliers (List of suppliers), ServiceApis (List of service apis), From (Start date of search - YYYY-MM-DD HH:mm:ss), To (End date of search - YYYY-MM-DD HH:mm:ss)
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}
