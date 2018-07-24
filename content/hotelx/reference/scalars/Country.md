{
  "title": "Country",
  "description": "",
  "weight": 1,
  "fields": null,
  "requireby": [
    {
      "name": "Location",
      "description": "Indicates the location of the hotel",
      "url": "undefined/objects/location"
    },
    {
      "name": "CriteriaSearch",
      "description": "Search criteria contains destination, travel dates and the number of pax in each room.",
      "url": "undefined/objects/criteriasearch"
    }
  ],
  "enumValues": null,
  "operator": "scalar",
  "typename": "Country",
  "hideGithubLink": true
}
The Country type represents Country values. A good example might be a Passenger Nationality.
In queries or mutations, Country fields have to be specified in ISO 3166-1 alpha-2 format with enclosing double quotes "ES".
## GraphQL schema definition

{{% graphql-schema-scalar %}}

## Required by

{{% graphql-require-by %}}
