{
  "title": "ID",
  "description": "",
  "weight": 1,
  "fields": null,
  "requireby": [
    {
      "name": "Board",
      "description": "Board type.",
      "url": "/hotelx/reference/objects/board"
    },
    {
      "name": "BoardData",
      "description": "Board data",
      "url": "/hotelx/reference/objects/boarddata"
    },
    {
      "name": "Category",
      "description": "Category Type",
      "url": "/hotelx/reference/objects/category"
    },
    {
      "name": "CategoryData",
      "description": "Category data",
      "url": "/hotelx/reference/objects/categorydata"
    },
    {
      "name": "Hotel",
      "description": "Hotel Type",
      "url": "/hotelx/reference/objects/hotel"
    },
    {
      "name": "HotelData",
      "description": "Hotel data",
      "url": "/hotelx/reference/objects/hoteldata"
    },
    {
      "name": "AdviseMessage",
      "description": "",
      "url": "/hotelx/reference/interfaces/advisemessage"
    },
    {
      "name": "DestinationData",
      "description": "Information about destinantion",
      "url": "/hotelx/reference/objects/destinationdata"
    },
    {
      "name": "Airport",
      "description": "Airport Type",
      "url": "/hotelx/reference/objects/airport"
    },
    {
      "name": "AirportData",
      "description": "Information about the airport",
      "url": "/hotelx/reference/objects/airportdata"
    },
    {
      "name": "RoomStatic",
      "description": "Room Type",
      "url": "/hotelx/reference/objects/roomstatic"
    },
    {
      "name": "RoomData",
      "description": "Room data",
      "url": "/hotelx/reference/objects/roomdata"
    },
    {
      "name": "Destination",
      "description": "Destination Type",
      "url": "/hotelx/reference/objects/destination"
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
