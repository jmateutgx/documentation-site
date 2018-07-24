{
  "title": "ParameterInput",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "String!",
      "name": "key",
      "url": "undefined/scalars/string",
      "description": "Contains the keyword/Id to identify a parameter.\nThis information is mandatory.",
      "args": null
    },
    {
      "typeString": "String!",
      "name": "value",
      "url": "undefined/scalars/string",
      "description": "Contains the parameter values.\nThis information is mandatory.",
      "args": null
    }
  ],
  "requireby": [
    {
      "name": "AccessInput",
      "description": "Access input",
      "url": "undefined/inputobjects/accessinput"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "ParameterInput",
  "hideGithubLink": true
}
Parameters Input.
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
