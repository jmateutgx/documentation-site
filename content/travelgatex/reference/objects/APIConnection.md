{
  "title": "APIConnection",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "[APIEdge]",
      "name": "edges",
      "url": "undefined/objects/apiedge",
      "description": "",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "PageInfo!",
      "name": "pageInfo",
      "url": "undefined/objects/pageinfo",
      "description": "",
      "isDeprecated": false,
      "args": null
    }
  ],
  "requireby": [
    {
      "name": "AdminQuery",
      "description": "The admin query root of TravelgateX's GraphQL interface.",
      "url": "undefined/objects/adminquery"
    },
    {
      "name": "OrganizationData",
      "description": "",
      "url": "undefined/objects/organizationdata"
    },
    {
      "name": "GroupCommonData",
      "description": "",
      "url": "undefined/interfaces/groupcommondata"
    },
    {
      "name": "GroupData",
      "description": "",
      "url": "undefined/objects/groupdata"
    },
    {
      "name": "ResourceData",
      "description": "",
      "url": "undefined/objects/resourcedata"
    },
    {
      "name": "ProductData",
      "description": "",
      "url": "undefined/objects/productdata"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "APIConnection",
  "hideGithubLink": true
}
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
