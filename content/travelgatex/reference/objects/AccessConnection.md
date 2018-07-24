{
  "title": "AccessConnection",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "[AccessEdge]",
      "name": "edges",
      "url": "undefined/objects/accessedge",
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
      "name": "SupplierData",
      "description": "",
      "url": "undefined/objects/supplierdata"
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
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "AccessConnection",
  "hideGithubLink": true
}
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
