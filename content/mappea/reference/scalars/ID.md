{
  "title": "ID",
  "description": "",
  "weight": 1,
  "fields": null,
  "requireby": [
    {
      "name": "MappeaMapSupplierInput",
      "description": "# MapSupplier",
      "url": "undefined/inputobjects/mappeamapsupplierinput"
    },
    {
      "name": "SupplierDetected",
      "description": "",
      "url": "undefined/objects/supplierdetected"
    },
    {
      "name": "Supplier",
      "description": "A Supplier is a Partner who is connected to TravelgateX on the supply side in order to sell their product to connected Buyers",
      "url": "undefined/objects/supplier"
    },
    {
      "name": "SupplierData",
      "description": "",
      "url": "undefined/objects/supplierdata"
    },
    {
      "name": "Provider",
      "description": "Temporary type to use only during SQL server's lifetime",
      "url": "undefined/objects/provider"
    },
    {
      "name": "Access",
      "description": "An Access is a set of credentials and configuration in order to access the system of a Supplier.",
      "url": "undefined/objects/access"
    },
    {
      "name": "AccessData",
      "description": "",
      "url": "undefined/objects/accessdata"
    },
    {
      "name": "Parameter",
      "description": "Parameters for additional information for the supplier's configuration.",
      "url": "undefined/objects/parameter"
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
