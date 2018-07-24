{
  "title": "GroupConnection",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "[GroupEdge]",
      "name": "edges",
      "url": "undefined/objects/groupedge",
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
      "name": "MemberData",
      "description": "",
      "url": "undefined/objects/memberdata"
    },
    {
      "name": "APIData",
      "description": "",
      "url": "undefined/objects/apidata"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "GroupConnection",
  "hideGithubLink": true
}
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
