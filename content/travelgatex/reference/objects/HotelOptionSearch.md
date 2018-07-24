{
  "title": "HotelOptionSearch",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "String!",
      "name": "supplierCode",
      "url": "undefined/scalars/string",
      "description": "Supplier that offers this option.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String!",
      "name": "accessCode",
      "url": "undefined/scalars/string",
      "description": "Access code of this option.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String!",
      "name": "market",
      "url": "undefined/scalars/string",
      "description": "Market of this option.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String!",
      "name": "hotelCode",
      "url": "undefined/scalars/string",
      "description": "Code of the hotel in the context selected.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String!",
      "name": "hotelCodeSupplier",
      "url": "undefined/scalars/string",
      "description": "Supplier's hotel code.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String",
      "name": "hotelName",
      "url": "undefined/scalars/string",
      "description": "Name of the hotel.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String!",
      "name": "boardCode",
      "url": "undefined/scalars/string",
      "description": "Code of the board in the context selected.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String!",
      "name": "boardCodeSupplier",
      "url": "undefined/scalars/string",
      "description": "Supplier's board code.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "PaymentType!",
      "name": "paymentType",
      "url": "undefined/enums/paymenttype",
      "description": "Indicates the payment type of the option returned. Possible options: Merchant, Direct, Card Booking, Card check in and Mixed.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "StatusType!",
      "name": "status",
      "url": "undefined/enums/statustype",
      "description": "The possible values in status in response are Available (OK) or On Request (RQ).",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "[Occupancy!]!",
      "name": "occupancies",
      "url": "undefined/objects/occupancy",
      "description": "List of occupancies for the request",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "[Room!]!",
      "name": "rooms",
      "url": "undefined/objects/room",
      "description": "List of rooms of the option returned.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Price!",
      "name": "price",
      "url": "undefined/objects/price",
      "description": "Specifies the prices (Gross, Net and Amount) of the option returned.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "[Supplement!]",
      "name": "supplements",
      "url": "undefined/objects/supplement",
      "description": "List of supplements of the option returned.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "[Surcharge!]",
      "name": "surcharges",
      "url": "undefined/objects/surcharge",
      "description": "List of surcharges of the option returned.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "[RateRulesType!]",
      "name": "rateRules",
      "url": "undefined/enums/raterulestype",
      "description": "Specifies rate rules of the option returned.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "CancelPolicy",
      "name": "cancelPolicy",
      "url": "undefined/objects/cancelpolicy",
      "description": "Specifies cancel policies of the option returned.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String",
      "name": "remarks",
      "url": "undefined/scalars/string",
      "description": "Additional information about the option.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "AddOns",
      "name": "addOns",
      "url": "undefined/objects/addons",
      "description": "Additional information about the option",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String!",
      "name": "token",
      "url": "undefined/scalars/string",
      "description": "Token for Deep Link",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String!",
      "name": "id",
      "url": "undefined/scalars/string",
      "description": "Indicates the quote key",
      "isDeprecated": false,
      "args": null
    }
  ],
  "requireby": null,
  "enumValues": null,
  "operator": "type",
  "typename": "HotelOptionSearch",
  "hideGithubLink": true
}
An option includes hotel information, meal plan, total price, conditions and room description
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}
