{
  "title": "Boolean",
  "description": "",
  "weight": 1,
  "fields": null,
  "requireby": [
    {
      "name": "PageInfo",
      "description": "",
      "url": "undefined/objects/pageinfo"
    },
    {
      "name": "OperationDetailed",
      "description": "Stats information per operation",
      "url": "undefined/objects/operationdetailed"
    },
    {
      "name": "AccessData",
      "description": "",
      "url": "undefined/objects/accessdata"
    },
    {
      "name": "SupplierData",
      "description": "",
      "url": "undefined/objects/supplierdata"
    },
    {
      "name": "Provider",
      "description": "Temporary type to use only during SQL server's lifetime",
      "url": "undefined/objects/provider"
    },
    {
      "name": "ClientData",
      "description": "",
      "url": "undefined/objects/clientdata"
    },
    {
      "name": "APIData",
      "description": "",
      "url": "undefined/objects/apidata"
    },
    {
      "name": "GroupData",
      "description": "",
      "url": "undefined/objects/groupdata"
    },
    {
      "name": "Member",
      "description": "You grant access to members which can be either:\nUsers: A developer, administrator or any other person from your Organization who interacts with the TravelgateX Platform. An email address can be used as the identity of a User.\nService Accounts: An application (Client) instead of an individual User. If you prefer, you can create as many Service Accounts as needed to represent different logical components of your application.",
      "url": "undefined/objects/member"
    },
    {
      "name": "RoleData",
      "description": "",
      "url": "undefined/objects/roledata"
    },
    {
      "name": "ResourceData",
      "description": "",
      "url": "undefined/objects/resourcedata"
    }
  ],
  "enumValues": null,
  "operator": "scalar",
  "typename": "Boolean",
  "hideGithubLink": true
}
The `Boolean` scalar type represents `true` or `false`.
## GraphQL schema definition

{{% graphql-schema-scalar %}}

## Required by

{{% graphql-require-by %}}
