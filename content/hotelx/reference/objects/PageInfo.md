{
  "title": "PageInfo",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "Boolean!",
      "name": "hasNextPage",
      "url": "undefined/scalars/boolean",
      "description": "",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Boolean!",
      "name": "hasPreviousPage",
      "url": "undefined/scalars/boolean",
      "description": "",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String!",
      "name": "startCursor",
      "url": "undefined/scalars/string",
      "description": "",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String!",
      "name": "endCursor",
      "url": "undefined/scalars/string",
      "description": "",
      "isDeprecated": false,
      "args": null
    }
  ],
  "requireby": [
    {
      "name": "BoardConnection",
      "description": "BoardList definition",
      "url": "undefined/objects/boardconnection"
    },
    {
      "name": "CategoryConnection",
      "description": "CategoryList definition",
      "url": "undefined/objects/categoryconnection"
    },
    {
      "name": "HotelConnection",
      "description": "HotelList definition",
      "url": "undefined/objects/hotelconnection"
    },
    {
      "name": "RoomConnection",
      "description": "RoomList definition",
      "url": "undefined/objects/roomconnection"
    },
    {
      "name": "DestinationConnection",
      "description": "DestinationList definition",
      "url": "undefined/objects/destinationconnection"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "PageInfo",
  "hideGithubLink": true
}
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
