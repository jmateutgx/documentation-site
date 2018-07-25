{
  "title": "Boolean",
  "description": "",
  "weight": 1,
  "fields": null,
  "requireby": [
    {
      "name": "PageInfo",
      "description": "",
      "url": "/hotelx/reference/objects/pageinfo"
    },
    {
      "name": "HotelData",
      "description": "Hotel data",
      "url": "/hotelx/reference/objects/hoteldata"
    },
    {
      "name": "DestinationData",
      "description": "Information about destinantion",
      "url": "/hotelx/reference/objects/destinationdata"
    },
    {
      "name": "Room",
      "description": "Contains the room information of the option returned.",
      "url": "/hotelx/reference/objects/room"
    },
    {
      "name": "Price",
      "description": "Price indicates the value of the room/option.\nSupplements and/or surcharges can be included into the price, and will be verified with nodes Supplements/Surcharges.",
      "url": "/hotelx/reference/objects/price"
    },
    {
      "name": "Supplement",
      "description": "Supplement that it can be or its already added to the option returned. Contains all the information about the supplement.",
      "url": "/hotelx/reference/objects/supplement"
    },
    {
      "name": "Surcharge",
      "description": "Surcharge that it can be or it is already added to the option returned. Contains all the information about the surcharge.",
      "url": "/hotelx/reference/objects/surcharge"
    },
    {
      "name": "CancelPolicy",
      "description": "Information about a policy cancellation.",
      "url": "/hotelx/reference/objects/cancelpolicy"
    },
    {
      "name": "Bed",
      "description": "Contains information about a bed.",
      "url": "/hotelx/reference/objects/bed"
    },
    {
      "name": "Markup",
      "description": "Informs markup applied over supplier price.",
      "url": "/hotelx/reference/objects/markup"
    }
  ],
  "enumValues": null,
  "operator": "scalar",
  "typename": "Boolean",
  "hideGithubLink": true
}
The `Boolean` scalar type represents `true` or `false`.
## GraphQL schema definition

{{% graphql-schema-scalar %}}

## Required by

{{% graphql-require-by %}}
