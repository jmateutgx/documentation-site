{
  "title": "AccessConnectUserInput",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "String!",
      "name": "code",
      "url": "undefined/scalars/string",
      "description": "connect user code",
      "args": null
    },
    {
      "typeString": "Boolean!",
      "name": "isActive",
      "url": "undefined/scalars/boolean",
      "description": "Indicates if the connect user is active.",
      "args": null
    },
    {
      "typeString": "[ConnectUserGroupInput!]",
      "name": "groups",
      "url": "undefined/inputobjects/connectusergroupinput",
      "description": "groups related to this connect user",
      "args": null
    }
  ],
  "requireby": null,
  "enumValues": null,
  "operator": "type",
  "typename": "AccessConnectUserInput",
  "hideGithubLink": true
}
Connect user input for data access management API
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}
