{
  "title": "HotelEdge",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "String!",
      "name": "cursor",
      "url": "undefined/scalars/string",
      "description": "",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Hotel",
      "name": "node",
      "url": "undefined/objects/hotel",
      "description": "",
      "isDeprecated": false,
      "args": null
    }
  ],
  "requireby": [
    {
      "name": "HotelConnection",
      "description": "HotelList definition",
      "url": "undefined/objects/hotelconnection"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "HotelEdge",
  "hideGithubLink": true
}
HotelList Edge definition
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
