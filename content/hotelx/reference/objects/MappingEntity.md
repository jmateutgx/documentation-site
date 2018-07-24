{
  "title": "MappingEntity",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "String!",
      "name": "code",
      "url": "undefined/scalars/string",
      "description": "Client code",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "[Map!]",
      "name": "contexts",
      "url": "undefined/objects/map",
      "description": "You can filter by output context.",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "[String!]",
          "name": "codes",
          "url": "undefined/scalars/string",
          "description": ""
        }
      ]
    }
  ],
  "requireby": null,
  "enumValues": null,
  "operator": "type",
  "typename": "MappingEntity",
  "hideGithubLink": true
}
Mapping about client codes with the equivalence per supplier.
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}
