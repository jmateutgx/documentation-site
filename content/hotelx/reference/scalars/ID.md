{
  "title": "ID",
  "description": "",
  "weight": 1,
  "fields": null,
  "requireby": [
    {
      "name": "HotelXBoardQueryInput",
      "description": "",
      "url": "undefined/inputobjects/hotelxboardqueryinput"
    },
    {
      "name": "HotelXCategoryQueryInput",
      "description": "",
      "url": "undefined/inputobjects/hotelxcategoryqueryinput"
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
      "name": "Board",
      "description": "Board type.",
      "url": "undefined/objects/board"
    },
    {
      "name": "BoardData",
      "description": "Board data",
      "url": "undefined/objects/boarddata"
    },
    {
      "name": "Category",
      "description": "Category Type",
      "url": "undefined/objects/category"
    },
    {
      "name": "CategoryData",
      "description": "Category data",
      "url": "undefined/objects/categorydata"
    },
    {
      "name": "Hotel",
      "description": "Hotel Type",
      "url": "undefined/objects/hotel"
    },
    {
      "name": "HotelData",
      "description": "Hotel data",
      "url": "undefined/objects/hoteldata"
    },
    {
      "name": "AdviseMessage",
      "description": "List of advise messages.",
      "url": "undefined/interfaces/advisemessage"
    },
    {
      "name": "DestinationData",
      "description": "Information about destinantion",
      "url": "undefined/objects/destinationdata"
    },
    {
      "name": "Airport",
      "description": "Airport Type",
      "url": "undefined/objects/airport"
    },
    {
      "name": "AirportData",
      "description": "Information about the airport",
      "url": "undefined/objects/airportdata"
    },
    {
      "name": "RoomStatic",
      "description": "Room Type",
      "url": "undefined/objects/roomstatic"
    },
    {
      "name": "RoomData",
      "description": "Room data",
      "url": "undefined/objects/roomdata"
    },
    {
      "name": "Destination",
      "description": "Destination Type",
      "url": "undefined/objects/destination"
    }
  ],
  "enumValues": null,
  "operator": "scalar",
  "typename": "ID",
  "hideGithubLink": true
}
The `ID` scalar type represents a unique identifier, often used to refetch an object or as key for a cache. The ID type appears in a JSON response as a String; however, it is not intended to be human-readable. When expected as an input type, any string (such as `"4"`) or integer (such as `4`) input value will be accepted as an ID.
## GraphQL schema definition

{{% graphql-schema-scalar %}}

## Required by

{{% graphql-require-by %}}
