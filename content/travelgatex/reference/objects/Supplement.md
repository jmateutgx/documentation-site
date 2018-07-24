{
  "title": "Supplement",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "String!",
      "name": "code",
      "url": "undefined/scalars/string",
      "description": "Specifies the supplement code.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String",
      "name": "name",
      "url": "undefined/scalars/string",
      "description": "Specifies the supplement name.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String",
      "name": "description",
      "url": "undefined/scalars/string",
      "description": "Specifies the supplement description.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "SupplementType!",
      "name": "supplementType",
      "url": "undefined/enums/supplementtype",
      "description": "Indicates the supplement type. Possible types: Fee, Ski_pass, Lessons, Meals, Equipment, Ticket, Transfers, Gla, Activity or Null.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "ChargeType!",
      "name": "chargeType",
      "url": "undefined/enums/chargetype",
      "description": "Indicates the charge types. We need to know whether the supplements have to be paid when the consumer gets to the hotel or beforehand.\nPossible charge types: Include or Exclude.\nwhen include: this supplement is mandatory and included in the option's price\nwhen exclude: this supplement is not included in the option's price",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Boolean!",
      "name": "mandatory",
      "url": "undefined/scalars/boolean",
      "description": "Indicates if the supplement is mandatory or not. If mandatory, this supplement will be applied to this option\nif the chargeType is excluded the customer will have to pay it directly at the hotel",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "DurationType",
      "name": "durationType",
      "url": "undefined/enums/durationtype",
      "description": "Specifies the duration type. Possible duration types: Range (specified dates) or Open. This field is mandatory for PDI.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Int",
      "name": "quantity",
      "url": "undefined/scalars/int",
      "description": "Indicates the quantity of field in the element \"unit\".",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "UnitTimeType",
      "name": "unit",
      "url": "undefined/enums/unittimetype",
      "description": "Indicates the unit type. Possible unit types: Day or Hour.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Date",
      "name": "effectiveDate",
      "url": "undefined/scalars/date",
      "description": "Indicates the effective date of the supplement.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Date",
      "name": "expireDate",
      "url": "undefined/scalars/date",
      "description": "Indicates the expire date of the supplement.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Resort",
      "name": "resort",
      "url": "undefined/objects/resort",
      "description": "Contains information about the resort",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Price",
      "name": "price",
      "url": "undefined/objects/price",
      "description": "Indicates the supplement price.",
      "isDeprecated": false,
      "args": null
    }
  ],
  "requireby": null,
  "enumValues": null,
  "operator": "type",
  "typename": "Supplement",
  "hideGithubLink": true
}
Supplement that it can be or its already added to the option returned. Contains all the information about the supplement.
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}
