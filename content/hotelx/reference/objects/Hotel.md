{
  "title": "Hotel",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "ID!",
      "name": "code",
      "url": "undefined/scalars/id",
      "description": "Hotel ID",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "HotelData",
      "name": "hotelData",
      "url": "undefined/objects/hoteldata",
      "description": "Hotel data",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "[AdviseMessage!]",
      "name": "error",
      "url": "undefined/interfaces/advisemessage",
      "description": "Errors that abort services",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "DateTime!",
      "name": "createdAt",
      "url": "undefined/scalars/datetime",
      "description": "Date created",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "DateTime!",
      "name": "updatedAt",
      "url": "undefined/scalars/datetime",
      "description": "Date updated",
      "isDeprecated": false,
      "args": null
    }
  ],
  "requireby": [
    {
      "name": "HotelEdge",
      "description": "HotelList Edge definition",
      "url": "undefined/objects/hoteledge"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "Hotel",
  "hideGithubLink": true
}
Hotel Type
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
