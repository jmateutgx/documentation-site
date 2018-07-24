{
  "title": "MappeaMutation",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "OnlyStatusResponse!",
      "name": "confirmUpload",
      "url": "undefined/objects/onlystatusresponse",
      "description": "",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "MappeaConfirmUploadInput!",
          "name": "input",
          "url": "undefined/inputobjects/mappeaconfirmuploadinput",
          "description": ""
        }
      ]
    },
    {
      "typeString": "UploadFileResponse!",
      "name": "uploadFile",
      "url": "undefined/objects/uploadfileresponse",
      "description": "",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "MappeaUploadFileInput!",
          "name": "input",
          "url": "undefined/inputobjects/mappeauploadfileinput",
          "description": ""
        }
      ]
    },
    {
      "typeString": "OnlyStatusResponse!",
      "name": "mapSupplier",
      "url": "undefined/objects/onlystatusresponse",
      "description": "",
      "isDeprecated": false,
      "args": [
        {
          "typeString": "MappeaMapSupplierInput!",
          "name": "input",
          "url": "undefined/inputobjects/mappeamapsupplierinput",
          "description": ""
        }
      ]
    }
  ],
  "requireby": [
    {
      "name": "Mutation",
      "description": "The root query for implementing GraphQL mutations. Mutations are operations that change or update data on the server",
      "url": "undefined/schema/mutation"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "MappeaMutation",
  "hideGithubLink": true
}
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
