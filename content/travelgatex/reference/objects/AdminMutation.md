{
  "title": "AdminMutation",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "Access",
      "name": "createAccess",
      "url": "undefined/objects/access",
      "description": "Creates an Access",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "AccessInput!",
          "name": "input",
          "url": "undefined/inputobjects/accessinput",
          "description": ""
        }
      ]
    },
    {
      "typeString": "Access",
      "name": "updateAccess",
      "url": "undefined/objects/access",
      "description": "Updates an Access",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "AccessInput!",
          "name": "input",
          "url": "undefined/inputobjects/accessinput",
          "description": ""
        }
      ]
    },
    {
      "typeString": "Access",
      "name": "grantAccessToGroup",
      "url": "undefined/objects/access",
      "description": "Grants Access visibility to a group",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "GroupInput!",
          "name": "input",
          "url": "undefined/inputobjects/groupinput",
          "description": ""
        }
      ]
    },
    {
      "typeString": "Access",
      "name": "deleteAccessFromGroup",
      "url": "undefined/objects/access",
      "description": "Removes Access visibility to groups",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "GroupInput!",
          "name": "input",
          "url": "undefined/inputobjects/groupinput",
          "description": ""
        }
      ]
    },
    {
      "typeString": "Supplier",
      "name": "grantSupplierToGroup",
      "url": "undefined/objects/supplier",
      "description": "Grants Supplier visibility to a group",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "GroupInput!",
          "name": "input",
          "url": "undefined/inputobjects/groupinput",
          "description": ""
        }
      ]
    },
    {
      "typeString": "Supplier",
      "name": "deleteSupplierFromGroup",
      "url": "undefined/objects/supplier",
      "description": "Removes Supplier visibility to groups",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "GroupInput!",
          "name": "input",
          "url": "undefined/inputobjects/groupinput",
          "description": ""
        }
      ]
    },
    {
      "typeString": "Client",
      "name": "grantClientToGroup",
      "url": "undefined/objects/client",
      "description": "Grants Client visibility to a group.",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "GroupInput!",
          "name": "input",
          "url": "undefined/inputobjects/groupinput",
          "description": ""
        }
      ]
    },
    {
      "typeString": "Client",
      "name": "deleteClientFromGroup",
      "url": "undefined/objects/client",
      "description": "Removes Client visibility to groups.",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "GroupInput!",
          "name": "input",
          "url": "undefined/inputobjects/groupinput",
          "description": ""
        }
      ]
    },
    {
      "typeString": "Client",
      "name": "createClient",
      "url": "undefined/objects/client",
      "description": "Creates a Client.",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "CreateClientInput!",
          "name": "input",
          "url": "undefined/inputobjects/createclientinput",
          "description": ""
        }
      ]
    },
    {
      "typeString": "Client",
      "name": "updateClient",
      "url": "undefined/objects/client",
      "description": "Updates a Client.",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "UpdateClientInput!",
          "name": "input",
          "url": "undefined/inputobjects/updateclientinput",
          "description": ""
        }
      ]
    },
    {
      "typeString": "Profile",
      "name": "createProfile",
      "url": "undefined/objects/profile",
      "description": "Creates a Profile.",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "CreateProfileInput!",
          "name": "input",
          "url": "undefined/inputobjects/createprofileinput",
          "description": ""
        }
      ]
    },
    {
      "typeString": "Profile",
      "name": "updateProfile",
      "url": "undefined/objects/profile",
      "description": "Updates a Profile.",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "UpdateProfileInput!",
          "name": "input",
          "url": "undefined/inputobjects/updateprofileinput",
          "description": ""
        }
      ]
    },
    {
      "typeString": "Profile",
      "name": "addEntitiesToProfile",
      "url": "undefined/objects/profile",
      "description": "Adds entities to a Profile.",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "UpdateEntitiesInput!",
          "name": "input",
          "url": "undefined/inputobjects/updateentitiesinput",
          "description": ""
        }
      ]
    },
    {
      "typeString": "Profile",
      "name": "removeEntitiesFromProfile",
      "url": "undefined/objects/profile",
      "description": "Removes entities from a Profile.",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "UpdateEntitiesInput!",
          "name": "input",
          "url": "undefined/inputobjects/updateentitiesinput",
          "description": ""
        }
      ]
    },
    {
      "typeString": "Organization!",
      "name": "createOrganization",
      "url": "undefined/objects/organization",
      "description": "Create organization. Require an user to be specified as the owner of the group.",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "CreateOrganizationInput!",
          "name": "organization",
          "url": "undefined/inputobjects/createorganizationinput",
          "description": ""
        }
      ]
    },
    {
      "typeString": "Member!",
      "name": "createMember",
      "url": "undefined/objects/member",
      "description": "Create member; requires specific group and role",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "CreateMemberInput!",
          "name": "member",
          "url": "undefined/inputobjects/creatememberinput",
          "description": ""
        }
      ]
    },
    {
      "typeString": "Group!",
      "name": "createGroup",
      "url": "undefined/objects/group",
      "description": "Create group; group \"owner\" is optional",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "CreateGroupInput!",
          "name": "group",
          "url": "undefined/inputobjects/creategroupinput",
          "description": ""
        }
      ]
    },
    {
      "typeString": "Member!",
      "name": "updateMember",
      "url": "undefined/objects/member",
      "description": "Update member additions or remove roles",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "UpdateMemberInput!",
          "name": "member",
          "url": "undefined/inputobjects/updatememberinput",
          "description": ""
        }
      ]
    },
    {
      "typeString": "Group!",
      "name": "updateGroup",
      "url": "undefined/objects/group",
      "description": "Update group additions or remove APIs",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "UpdateGroupInput!",
          "name": "group",
          "url": "undefined/inputobjects/updategroupinput",
          "description": ""
        },
        {
          "typeString": "Method!",
          "name": "method",
          "url": "undefined/enums/method",
          "description": ""
        }
      ]
    },
    {
      "typeString": "Member!",
      "name": "deleteMember",
      "url": "undefined/objects/member",
      "description": "Delete a member from specific group",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "[DeleteMemberInput!]!",
          "name": "member",
          "url": "undefined/inputobjects/deletememberinput",
          "description": ""
        }
      ]
    },
    {
      "typeString": "Group!",
      "name": "deleteGroup",
      "url": "undefined/objects/group",
      "description": "Delete group and members from this group",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "DeleteGroupInput!",
          "name": "group",
          "url": "undefined/inputobjects/deletegroupinput",
          "description": ""
        }
      ]
    }
  ],
  "requireby": [
    {
      "name": "Mutation",
      "description": "The root query for implementing GraphQL mutations. Mutations are operations that change or update data on the server",
      "url": "undefined/schema/mutation"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "AdminMutation",
  "hideGithubLink": true
}
The admin query root of TravelgateX's for implementing GraphQL mutations.
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
