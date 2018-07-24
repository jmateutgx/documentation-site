{
  "title": "AdviseMessage",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "ID!",
      "name": "code",
      "url": "undefined/scalars/id",
      "description": "AM code: The following codes can be returned:",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String!",
      "name": "type",
      "url": "undefined/scalars/string",
      "description": "Error type: The following types are valid:",
      "isDeprecated": true,
      "args": null,
      "deprecationReason": "",
      "descriptionSplitted": {
        "date": "2018-06-01",
        "first": "deprecated from",
        "second": ""
      },
      "deprecationDate": "2018-06-01"
    },
    {
      "typeString": "String!",
      "name": "description",
      "url": "undefined/scalars/string",
      "description": "Error description",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "AdviseMessageLevel!",
      "name": "level",
      "url": "undefined/enums/advisemessagelevel",
      "description": "Indicates the level of importance of the message: Posible values ERROR WARN INFO",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "ExternalMessage",
      "name": "external",
      "url": "undefined/objects/externalmessage",
      "description": "Specify the external message.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "ID!",
      "name": "correlationID",
      "url": "undefined/scalars/id",
      "description": "Identifier to be able to investigate the cause of the error",
      "isDeprecated": false,
      "args": null
    }
  ],
  "requireby": null,
  "enumValues": null,
  "operator": "interface",
  "typename": "AdviseMessage",
  "hideGithubLink": true
}
List of advise messages.
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}
