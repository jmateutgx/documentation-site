{
  "title": "Int",
  "description": "",
  "weight": 1,
  "fields": null,
  "requireby": [
    {
      "name": "RelayInput",
      "description": "",
      "url": "undefined/inputobjects/relayinput"
    },
    {
      "name": "HotelXHotelListInput",
      "description": "",
      "url": "undefined/inputobjects/hotelxhotellistinput"
    },
    {
      "name": "HotelXRoomQueryInput",
      "description": "",
      "url": "undefined/inputobjects/hotelxroomqueryinput"
    },
    {
      "name": "HotelXDestinationListInput",
      "description": "",
      "url": "undefined/inputobjects/hotelxdestinationlistinput"
    },
    {
      "name": "HotelXDestinationSearcherInput",
      "description": "",
      "url": "undefined/inputobjects/hotelxdestinationsearcherinput"
    },
    {
      "name": "StatsRequest",
      "description": "Contains internal information.",
      "url": "undefined/objects/statsrequest"
    },
    {
      "name": "StatAccess",
      "description": "",
      "url": "undefined/objects/stataccess"
    },
    {
      "name": "Pax",
      "description": "Specifies the age pax. The range of what is considered an adult, infant or baby is particular to each supplier.",
      "url": "undefined/objects/pax"
    },
    {
      "name": "Occupancy",
      "description": "Information about occupancy.",
      "url": "undefined/objects/occupancy"
    },
    {
      "name": "Room",
      "description": "Contains the room information of the option returned.",
      "url": "undefined/objects/room"
    },
    {
      "name": "Supplement",
      "description": "Supplement that it can be or its already added to the option returned. Contains all the information about the supplement.",
      "url": "undefined/objects/supplement"
    },
    {
      "name": "Bed",
      "description": "Contains information about a bed.",
      "url": "undefined/objects/bed"
    },
    {
      "name": "CancelPenalty",
      "description": "Contains information for cancellation penalities..",
      "url": "undefined/objects/cancelpenalty"
    },
    {
      "name": "BookingRoom",
      "description": "",
      "url": "undefined/objects/bookingroom"
    }
  ],
  "enumValues": null,
  "operator": "scalar",
  "typename": "Int",
  "hideGithubLink": true
}
The `Int` scalar type represents non-fractional signed whole numeric values. Int can represent values between -(2^31) and 2^31 - 1. 
## GraphQL schema definition

{{% graphql-schema-scalar %}}

## Required by

{{% graphql-require-by %}}
