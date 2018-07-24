{
  "title": "DateTime",
  "description": "",
  "weight": 1,
  "fields": null,
  "requireby": [
    {
      "name": "Board",
      "description": "Board type.",
      "url": "undefined/objects/board"
    },
    {
      "name": "Category",
      "description": "Category Type",
      "url": "undefined/objects/category"
    },
    {
      "name": "Hotel",
      "description": "Hotel Type",
      "url": "undefined/objects/hotel"
    },
    {
      "name": "Media",
      "description": "Contains media information.",
      "url": "undefined/objects/media"
    },
    {
      "name": "Airport",
      "description": "Airport Type",
      "url": "undefined/objects/airport"
    },
    {
      "name": "RoomStatic",
      "description": "Room Type",
      "url": "undefined/objects/roomstatic"
    },
    {
      "name": "Destination",
      "description": "Destination Type",
      "url": "undefined/objects/destination"
    },
    {
      "name": "AuditData",
      "description": "Data sent and received in the supplier’s native format.",
      "url": "undefined/objects/auditdata"
    },
    {
      "name": "Stat",
      "description": "",
      "url": "undefined/objects/stat"
    },
    {
      "name": "Transactions",
      "description": "Supplier transaction",
      "url": "undefined/objects/transactions"
    }
  ],
  "enumValues": null,
  "operator": "scalar",
  "typename": "DateTime",
  "hideGithubLink": true
}
The DateTime type represents DateTime values. A good example might be a transaction TimeSpan.
In queries or mutations, DateTime fields have to be specified in ISO 8601 format with enclosing double quotes: "2017-10-22T13:57:31.123Z".
## GraphQL schema definition

{{% graphql-schema-scalar %}}

## Required by

{{% graphql-require-by %}}
