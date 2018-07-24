{
  "title": "PluginsInput",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "PluginType!",
      "name": "type",
      "url": "undefined/enums/plugintype",
      "description": "type of the plugins to execute",
      "args": null
    },
    {
      "typeString": "String!",
      "name": "name",
      "url": "undefined/scalars/string",
      "description": "name of plugin to execute",
      "args": null
    },
    {
      "typeString": "[ParameterInput!]",
      "name": "parameters",
      "url": "undefined/inputobjects/parameterinput",
      "description": "Plugin's parameters",
      "args": null
    }
  ],
  "requireby": null,
  "enumValues": null,
  "operator": "type",
  "typename": "PluginsInput",
  "hideGithubLink": true
}
Plugin to execute.
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}
