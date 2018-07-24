{
  "title": "AccessInput",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "String",
      "name": "name",
      "url": "undefined/scalars/string",
      "description": "Access descriptive unique name",
      "args": null
    },
    {
      "typeString": "Boolean",
      "name": "isActive",
      "url": "undefined/scalars/boolean",
      "description": "Indicates if Access is active",
      "args": null
    },
    {
      "typeString": "ID",
      "name": "code",
      "url": "undefined/scalars/id",
      "description": "Access code.",
      "args": null
    },
    {
      "typeString": "String",
      "name": "supplier",
      "url": "undefined/scalars/string",
      "description": "Supplier for this Access",
      "args": null
    },
    {
      "typeString": "Boolean",
      "name": "isTest",
      "url": "undefined/scalars/boolean",
      "description": "Indicates if Access can be used for testing or not",
      "args": null
    },
    {
      "typeString": "String",
      "name": "user",
      "url": "undefined/scalars/string",
      "description": "User code to connect to supplier",
      "args": null
    },
    {
      "typeString": "String",
      "name": "password",
      "url": "undefined/scalars/string",
      "description": "Password for the connection",
      "args": null
    },
    {
      "typeString": "UrlsInput",
      "name": "urls",
      "url": "undefined/inputobjects/urlsinput",
      "description": "Specific URLs",
      "args": null
    },
    {
      "typeString": "[ParameterInput]",
      "name": "parameters",
      "url": "undefined/inputobjects/parameterinput",
      "description": "List of parameters for additional information",
      "args": null
    },
    {
      "typeString": "[String!]",
      "name": "markets",
      "url": "undefined/scalars/string",
      "description": "Markets allowed for the Access",
      "args": null
    },
    {
      "typeString": "[RateRulesType!]",
      "name": "rateRules",
      "url": "undefined/enums/raterulestype",
      "description": "Business rule types for the Access",
      "args": null
    },
    {
      "typeString": "String",
      "name": "shared",
      "url": "undefined/scalars/string",
      "description": "Parent Access if Shared Access.",
      "args": null
    },
    {
      "typeString": "ID",
      "name": "group",
      "url": "undefined/scalars/id",
      "description": "Default group where the access will be visible.",
      "args": null
    }
  ],
  "requireby": null,
  "enumValues": null,
  "operator": "type",
  "typename": "AccessInput",
  "hideGithubLink": true
}
Access input
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}
