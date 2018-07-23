{
  "title": "Language",
  "description": "",
  "weight": 1,
  "fields": null,
  "requireby": [
    {
      "name": "Text",
      "description": "",
      "url": "/hotelx/reference/interfaces/text"
    },
    {
      "name": "CriteriaSearch",
      "description": "Search criteria contains destination, travel dates and the number of pax in each room.",
      "url": "/hotelx/reference/objects/criteriasearch"
    }
  ],
  "enumValues": null,
  "operator": "scalar",
  "typename": "Language",
  "hideGithubLink": true
}
The Language type represents Language values. A good example might be a Hotel Description Language.
In queries or mutations, Language fields have to be specified in ISO 3166-1 alpha-2 format with enclosing double quotes "es".
## GraphQL schema definition

{{% graphql-schema-scalar %}}

## Required by

{{% graphql-require-by %}}
