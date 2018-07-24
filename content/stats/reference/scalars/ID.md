{
  "title": "ID",
  "description": "",
  "weight": 1,
  "fields": null,
  "requireby": [
    {
      "name": "Stats",
      "description": "The service used to access the stats of every connection that uses the HUB",
      "url": "undefined/objects/stats"
    },
    {
      "name": "AdviseMessage",
      "description": "List of advise messages.",
      "url": "undefined/interfaces/advisemessage"
    },
    {
      "name": "Access",
      "description": "An Access is a set of credentials and configuration in order to access the system of a Supplier.",
      "url": "undefined/objects/access"
    },
    {
      "name": "Client",
      "description": "Client identifies who is making the request and holds the configuration assigned to it.",
      "url": "undefined/objects/client"
    },
    {
      "name": "AccessData",
      "description": "",
      "url": "undefined/objects/accessdata"
    },
    {
      "name": "Supplier",
      "description": "A Supplier is a Partner who is connected to TravelgateX on the supply side in order to sell their product to connected Buyers",
      "url": "undefined/objects/supplier"
    },
    {
      "name": "Parameter",
      "description": "Parameters for additional information for the supplier's configuration.",
      "url": "undefined/objects/parameter"
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
      "name": "Operation",
      "description": "",
      "url": "undefined/objects/operation"
    },
    {
      "name": "StatsInfo",
      "description": "Details of an specific error",
      "url": "undefined/objects/statsinfo"
    },
    {
      "name": "OperationData",
      "description": "",
      "url": "undefined/objects/operationdata"
    },
    {
      "name": "API",
      "description": "",
      "url": "undefined/objects/api"
    },
    {
      "name": "APIData",
      "description": "",
      "url": "undefined/objects/apidata"
    },
    {
      "name": "Group",
      "description": "Groups are organized hierarchically.",
      "url": "undefined/objects/group"
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
      "name": "MemberData",
      "description": "",
      "url": "undefined/objects/memberdata"
    },
    {
      "name": "Role",
      "description": "Permissions determine what operations are allowed on a resource",
      "url": "undefined/objects/role"
    },
    {
      "name": "RoleData",
      "description": "",
      "url": "undefined/objects/roledata"
    },
    {
      "name": "Resource",
      "description": "Resources are those used in APIs and Products.",
      "url": "undefined/objects/resource"
    },
    {
      "name": "ResourceData",
      "description": "",
      "url": "undefined/objects/resourcedata"
    }
  ],
  "enumValues": null,
  "operator": "scalar",
  "typename": "ID",
  "hideGithubLink": true
}
The `ID` scalar type represents a unique identifier, often used to refetch an object or as key for a cache. The ID type appears in a JSON response as a String; however, it is not intended to be human-readable. When expected as an input type, any string (such as `"4"`) or integer (such as `4`) input value will be accepted as an ID.
## GraphQL schema definition

{{% graphql-schema-scalar %}}

## Required by

{{% graphql-require-by %}}
