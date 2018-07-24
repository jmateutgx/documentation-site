{
  "title": "Coordinates",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "Float!",
      "name": "latitude",
      "url": "undefined/scalars/float",
      "description": "Latitude",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Float!",
      "name": "longitude",
      "url": "undefined/scalars/float",
      "description": "Longitude",
      "isDeprecated": false,
      "args": null
    }
  ],
  "requireby": [
    {
      "name": "Location",
      "description": "Indicates the location of the hotel",
      "url": "undefined/objects/location"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "Coordinates",
  "hideGithubLink": true
}
Geographical coordinates corresponding to a location.
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
