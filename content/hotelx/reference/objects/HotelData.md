{
  "title": "HotelData",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "ID!",
      "name": "code",
      "url": "undefined/scalars/id",
      "description": "Internal code.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String!",
      "name": "hotelCode",
      "url": "undefined/scalars/string",
      "description": "Code to perform availability.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String",
      "name": "hotelCodeSupplier",
      "url": "undefined/scalars/string",
      "description": "Native supplier hotel code.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String!",
      "name": "hotelName",
      "url": "undefined/scalars/string",
      "description": "Name of the hotel in the Supplier selected.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String!",
      "name": "categoryCode",
      "url": "undefined/scalars/string",
      "description": "Hotel category (for example number of stars).",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Property",
      "name": "property",
      "url": "undefined/objects/property",
      "description": "Indicates property type",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String",
      "name": "chainCode",
      "url": "undefined/scalars/string",
      "description": "Hotel chain code",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Boolean!",
      "name": "exclusiveDeal",
      "url": "undefined/scalars/boolean",
      "description": "Indicates that the Hotel has an Exclusive Deal.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Location!",
      "name": "location",
      "url": "undefined/objects/location",
      "description": "Indicates the location of the hotel",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Contact",
      "name": "contact",
      "url": "undefined/objects/contact",
      "description": "Contact cotains information about hotel contact.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "[Int!]!",
      "name": "rank",
      "url": "undefined/scalars/int",
      "description": "Rank indicates the supplier categorization.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "[String!]",
      "name": "cardTypes",
      "url": "undefined/scalars/string",
      "description": "List of credit cards",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "[Amenity!]",
      "name": "amenities",
      "url": "undefined/objects/amenity",
      "description": "Amenities",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "[Media!]",
      "name": "medias",
      "url": "undefined/objects/media",
      "description": "Medias",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "[Description!]",
      "name": "descriptions",
      "url": "undefined/objects/description",
      "description": "Descriptions",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "[DescriptionType!]",
          "name": "types",
          "url": "undefined/enums/descriptiontype",
          "description": ""
        },
        {
          "typeString": "[Language!]",
          "name": "languages",
          "url": "undefined/scalars/language",
          "description": ""
        }
      ]
    }
  ],
  "requireby": [
    {
      "name": "Hotel",
      "description": "Hotel Type",
      "url": "undefined/objects/hotel"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "HotelData",
  "hideGithubLink": true
}
Hotel data
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
