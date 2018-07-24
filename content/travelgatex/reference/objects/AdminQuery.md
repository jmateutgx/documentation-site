{
  "title": "AdminQuery",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "JWT",
      "name": "jwt",
      "url": "undefined/scalars/jwt",
      "description": "Get JSON Web Token (JWT) linked to Member",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "AccessConnection",
      "name": "accesses",
      "url": "undefined/objects/accessconnection",
      "description": "Obtain a list of accesses for a filter",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "Int",
          "name": "first",
          "url": "undefined/scalars/int",
          "description": ""
        },
        {
          "typeString": "Int",
          "name": "last",
          "url": "undefined/scalars/int",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "before",
          "url": "undefined/scalars/string",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "after",
          "url": "undefined/scalars/string",
          "description": ""
        },
        {
          "typeString": "AccessFilter",
          "name": "filter",
          "url": "undefined/inputobjects/accessfilter",
          "description": ""
        }
      ]
    },
    {
      "typeString": "SupplierConnection",
      "name": "suppliers",
      "url": "undefined/objects/supplierconnection",
      "description": "Obtain all suppliers for a filter.",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "Int",
          "name": "first",
          "url": "undefined/scalars/int",
          "description": ""
        },
        {
          "typeString": "Int",
          "name": "last",
          "url": "undefined/scalars/int",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "before",
          "url": "undefined/scalars/string",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "after",
          "url": "undefined/scalars/string",
          "description": ""
        },
        {
          "typeString": "SupplierFilter",
          "name": "filter",
          "url": "undefined/inputobjects/supplierfilter",
          "description": ""
        }
      ]
    },
    {
      "typeString": "ClientConnection",
      "name": "clients",
      "url": "undefined/objects/clientconnection",
      "description": "Obtain all clients for a filter.",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "Int",
          "name": "first",
          "url": "undefined/scalars/int",
          "description": ""
        },
        {
          "typeString": "Int",
          "name": "last",
          "url": "undefined/scalars/int",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "before",
          "url": "undefined/scalars/string",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "after",
          "url": "undefined/scalars/string",
          "description": ""
        },
        {
          "typeString": "ClientFilter",
          "name": "filter",
          "url": "undefined/inputobjects/clientfilter",
          "description": ""
        }
      ]
    },
    {
      "typeString": "ServiceApi",
      "name": "serviceApi",
      "url": "undefined/objects/serviceapi",
      "description": "Obtain a ServiceAPI",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "ServiceApiFilter",
          "name": "filter",
          "url": "undefined/inputobjects/serviceapifilter",
          "description": ""
        }
      ]
    },
    {
      "typeString": "PointOfSaleConnection",
      "name": "pointsOfSale",
      "url": "undefined/objects/pointofsaleconnection",
      "description": "Obtain all Points of Sale for the filters",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "PointOfSaleFilter",
          "name": "filter",
          "url": "undefined/inputobjects/pointofsalefilter",
          "description": ""
        }
      ]
    },
    {
      "typeString": "ProfileConnection",
      "name": "profiles",
      "url": "undefined/objects/profileconnection",
      "description": "Obtain all Profiles for the filters",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "ProfileFilter",
          "name": "filter",
          "url": "undefined/inputobjects/profilefilter",
          "description": ""
        }
      ]
    },
    {
      "typeString": "OrganizationConnection!",
      "name": "organizations",
      "url": "undefined/objects/organizationconnection",
      "description": "Organizations list; specify organization codes to filter organizations",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "[ID!]",
          "name": "codes",
          "url": "undefined/scalars/id",
          "description": ""
        },
        {
          "typeString": "Int",
          "name": "first",
          "url": "undefined/scalars/int",
          "description": ""
        },
        {
          "typeString": "Int",
          "name": "last",
          "url": "undefined/scalars/int",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "before",
          "url": "undefined/scalars/string",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "after",
          "url": "undefined/scalars/string",
          "description": ""
        }
      ]
    },
    {
      "typeString": "ProductConnection!",
      "name": "products",
      "url": "undefined/objects/productconnection",
      "description": "Product catalog; specify products codes to filter ",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "[ID!]",
          "name": "codes",
          "url": "undefined/scalars/id",
          "description": ""
        },
        {
          "typeString": "Int",
          "name": "first",
          "url": "undefined/scalars/int",
          "description": ""
        },
        {
          "typeString": "Int",
          "name": "last",
          "url": "undefined/scalars/int",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "before",
          "url": "undefined/scalars/string",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "after",
          "url": "undefined/scalars/string",
          "description": ""
        }
      ]
    },
    {
      "typeString": "MemberConnection!",
      "name": "members",
      "url": "undefined/objects/memberconnection",
      "description": "Members list; specify member codes to filter members.",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "[ID!]",
          "name": "codes",
          "url": "undefined/scalars/id",
          "description": ""
        },
        {
          "typeString": "MemberType",
          "name": "type",
          "url": "undefined/enums/membertype",
          "description": ""
        },
        {
          "typeString": "Int",
          "name": "first",
          "url": "undefined/scalars/int",
          "description": ""
        },
        {
          "typeString": "Int",
          "name": "last",
          "url": "undefined/scalars/int",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "before",
          "url": "undefined/scalars/string",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "after",
          "url": "undefined/scalars/string",
          "description": ""
        }
      ]
    },
    {
      "typeString": "GroupConnection!",
      "name": "groups",
      "url": "undefined/objects/groupconnection",
      "description": "Groups list; specify group codes to filter groups.",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "[ID!]",
          "name": "codes",
          "url": "undefined/scalars/id",
          "description": ""
        },
        {
          "typeString": "GroupType",
          "name": "type",
          "url": "undefined/enums/grouptype",
          "description": ""
        },
        {
          "typeString": "Int",
          "name": "first",
          "url": "undefined/scalars/int",
          "description": ""
        },
        {
          "typeString": "Int",
          "name": "last",
          "url": "undefined/scalars/int",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "before",
          "url": "undefined/scalars/string",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "after",
          "url": "undefined/scalars/string",
          "description": ""
        }
      ]
    },
    {
      "typeString": "APIConnection!",
      "name": "apis",
      "url": "undefined/objects/apiconnection",
      "description": "Apis list; specify api codes to filter apis.",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "[ID!]",
          "name": "codes",
          "url": "undefined/scalars/id",
          "description": ""
        },
        {
          "typeString": "Int",
          "name": "first",
          "url": "undefined/scalars/int",
          "description": ""
        },
        {
          "typeString": "Int",
          "name": "last",
          "url": "undefined/scalars/int",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "before",
          "url": "undefined/scalars/string",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "after",
          "url": "undefined/scalars/string",
          "description": ""
        }
      ]
    },
    {
      "typeString": "ResourceConnection!",
      "name": "resources",
      "url": "undefined/objects/resourceconnection",
      "description": "Resources list; specify resource codes to filter resources.",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "[ID!]",
          "name": "codes",
          "url": "undefined/scalars/id",
          "description": ""
        },
        {
          "typeString": "Int",
          "name": "first",
          "url": "undefined/scalars/int",
          "description": ""
        },
        {
          "typeString": "Int",
          "name": "last",
          "url": "undefined/scalars/int",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "before",
          "url": "undefined/scalars/string",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "after",
          "url": "undefined/scalars/string",
          "description": ""
        }
      ]
    },
    {
      "typeString": "RoleConnection!",
      "name": "roles",
      "url": "undefined/objects/roleconnection",
      "description": "Roles list; specify role codes to filter roles.",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "[ID!]",
          "name": "codes",
          "url": "undefined/scalars/id",
          "description": ""
        },
        {
          "typeString": "RoleType",
          "name": "type",
          "url": "undefined/enums/roletype",
          "description": ""
        },
        {
          "typeString": "Int",
          "name": "first",
          "url": "undefined/scalars/int",
          "description": ""
        },
        {
          "typeString": "Int",
          "name": "last",
          "url": "undefined/scalars/int",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "before",
          "url": "undefined/scalars/string",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "after",
          "url": "undefined/scalars/string",
          "description": ""
        }
      ]
    },
    {
      "typeString": "OperationConnection!",
      "name": "operations",
      "url": "undefined/objects/operationconnection",
      "description": "Operations list; specify operations codes to filter operations.",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "[ID!]",
          "name": "codes",
          "url": "undefined/scalars/id",
          "description": ""
        },
        {
          "typeString": "OperationType",
          "name": "type",
          "url": "undefined/enums/operationtype",
          "description": ""
        },
        {
          "typeString": "Int",
          "name": "first",
          "url": "undefined/scalars/int",
          "description": ""
        },
        {
          "typeString": "Int",
          "name": "last",
          "url": "undefined/scalars/int",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "before",
          "url": "undefined/scalars/string",
          "description": ""
        },
        {
          "typeString": "String",
          "name": "after",
          "url": "undefined/scalars/string",
          "description": ""
        }
      ]
    }
  ],
  "requireby": [
    {
      "name": "Query",
      "description": "The query root of TravelgateX's GraphQL interface.",
      "url": "undefined/schema/query"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "AdminQuery",
  "hideGithubLink": true
}
The admin query root of TravelgateX's GraphQL interface.
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
