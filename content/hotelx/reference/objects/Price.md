{
  "title": "Price",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "Currency!",
      "name": "currency",
      "url": "undefined/scalars/currency",
      "description": "Currency code indicating which currency should be paid.\nThis information is mandatory.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Boolean!",
      "name": "binding",
      "url": "undefined/scalars/boolean",
      "description": "It indicates if the price indicated in the gross must be respected.\nThat is, the customer can not sell the room / option at a price lower than that established by the supplier.\nThis information is mandatory.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Float!",
      "name": "net",
      "url": "undefined/scalars/float",
      "description": "Indicates the net price that the customer must pay to the supplier.\nThis information is mandatory.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Float",
      "name": "gross",
      "url": "undefined/scalars/float",
      "description": "Indicates the retail price that the supplier sells to the customer.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Exchange!",
      "name": "exchange",
      "url": "undefined/objects/exchange",
      "description": "Provides information about the currency of original, and its rate applied over the results returned by the Supplier.\nThis information is mandatory.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "[Markup!]",
      "name": "markups",
      "url": "undefined/objects/markup",
      "description": "Informs markup applied over supplier price.",
      "isDeprecated": false,
      "args": null
    }
  ],
  "requireby": [
    {
      "name": "HotelOptionSearch",
      "description": "An option includes hotel information, meal plan, total price, conditions and room description",
      "url": "undefined/objects/hoteloptionsearch"
    },
    {
      "name": "Supplement",
      "description": "Supplement that it can be or its already added to the option returned. Contains all the information about the supplement.",
      "url": "undefined/objects/supplement"
    },
    {
      "name": "Surcharge",
      "description": "Surcharge that it can be or it is already added to the option returned. Contains all the information about the surcharge.",
      "url": "undefined/objects/surcharge"
    },
    {
      "name": "RoomPrice",
      "description": "Specifies the room price.",
      "url": "undefined/objects/roomprice"
    },
    {
      "name": "PriceBreakdown",
      "description": "Information about daily price.",
      "url": "undefined/objects/pricebreakdown"
    },
    {
      "name": "HotelOptionQuote",
      "description": "Contains information about quote(s)",
      "url": "undefined/objects/hoteloptionquote"
    },
    {
      "name": "HotelBookingDetail",
      "description": "Contains information about booking",
      "url": "undefined/objects/hotelbookingdetail"
    },
    {
      "name": "BookingRoom",
      "description": "",
      "url": "undefined/objects/bookingroom"
    },
    {
      "name": "HotelCancelDetail",
      "description": "Contains information about cancel",
      "url": "undefined/objects/hotelcanceldetail"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "Price",
  "hideGithubLink": true
}
Price indicates the value of the room/option.
Supplements and/or surcharges can be included into the price, and will be verified with nodes Supplements/Surcharges.
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
