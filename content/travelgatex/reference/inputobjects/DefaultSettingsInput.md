{
  "title": "DefaultSettingsInput",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "String!",
      "name": "groupCode",
      "url": "undefined/scalars/string",
      "description": "Unique Id",
      "args": null
    },
    {
      "typeString": "String!",
      "name": "connectUser",
      "url": "undefined/scalars/string",
      "description": "This field is occurs only if the authorization header is of the type JWT.. It is used for to change the user that\nhas been set by default in the preload.",
      "args": null
    },
    {
      "typeString": "String",
      "name": "context",
      "url": "undefined/scalars/string",
      "description": "Indicates the context of the I/O codes (hotel, board, room and rates)",
      "args": null
    },
    {
      "typeString": "Language!",
      "name": "language",
      "url": "undefined/scalars/language",
      "description": "Language to be used in request",
      "args": null
    },
    {
      "typeString": "Currency!",
      "name": "currency",
      "url": "undefined/scalars/currency",
      "description": "Currency requested if supported by supplier",
      "args": null
    },
    {
      "typeString": "Country!",
      "name": "nationality",
      "url": "undefined/scalars/country",
      "description": "Nationality of the guest (use ISO3166_1_alfa_2)",
      "args": null
    },
    {
      "typeString": "String!",
      "name": "market",
      "url": "undefined/scalars/string",
      "description": "Targeted zone, country or point-ofsale-to be used in request.",
      "args": null
    },
    {
      "typeString": "TimeoutInput!",
      "name": "timeout",
      "url": "undefined/inputobjects/timeoutinput",
      "description": "Group of timeouts to be used in the differents services",
      "args": null
    },
    {
      "typeString": "DefaultSettingsBusinessRulesInput!",
      "name": "businessRules",
      "url": "undefined/inputobjects/defaultsettingsbusinessrulesinput",
      "description": "Business rules",
      "args": null
    }
  ],
  "requireby": null,
  "enumValues": null,
  "operator": "type",
  "typename": "DefaultSettingsInput",
  "hideGithubLink": true
}
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}
