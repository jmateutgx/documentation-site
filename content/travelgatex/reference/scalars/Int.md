{
  "title": "Int",
  "description": "",
  "weight": 1,
  "fields": null,
  "requireby": [
    {
      "name": "SupplierData",
      "description": "",
      "url": "undefined/objects/supplierdata"
    },
    {
      "name": "SupplierFilter",
      "description": "",
      "url": "undefined/inputobjects/supplierfilter"
    },
    {
      "name": "ServiceOperation",
      "description": "Information related to an API operation",
      "url": "undefined/objects/serviceoperation"
    },
    {
      "name": "GroupData",
      "description": "",
      "url": "undefined/objects/groupdata"
    },
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
      "name": "PaxInput",
      "description": "Pax object that contains the pax age.",
      "url": "undefined/inputobjects/paxinput"
    },
    {
      "name": "HotelSettingsInput",
      "description": "Settings that you can edit for this avail. Values are loaded by default in our Back Office.",
      "url": "undefined/inputobjects/hotelsettingsinput"
    },
    {
      "name": "BusinessRulesInput",
      "description": "List of business rules to use as filter on the options.",
      "url": "undefined/inputobjects/businessrulesinput"
    },
    {
      "name": "SettingsBaseInput",
      "description": "Contains the time out and business rules of a supplier or an access.",
      "url": "undefined/inputobjects/settingsbaseinput"
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
      "name": "Bed",
      "description": "Contains information about a bed.",
      "url": "undefined/objects/bed"
    },
    {
      "name": "Supplement",
      "description": "Supplement that it can be or its already added to the option returned. Contains all the information about the supplement.",
      "url": "undefined/objects/supplement"
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
    },
    {
      "name": "File",
      "description": "",
      "url": "undefined/objects/file"
    },
    {
      "name": "GetMappeaStatsData",
      "description": "",
      "url": "undefined/objects/getmappeastatsdata"
    },
    {
      "name": "ExpireDate",
      "description": "The card expiration date",
      "url": "undefined/objects/expiredate"
    },
    {
      "name": "Ratios",
      "description": "Ratios details",
      "url": "undefined/objects/ratios"
    },
    {
      "name": "OperationDetailed",
      "description": "Stats information per operation",
      "url": "undefined/objects/operationdetailed"
    },
    {
      "name": "StatsInfo",
      "description": "Details of an specific error",
      "url": "undefined/objects/statsinfo"
    },
    {
      "name": "StatsAssert",
      "description": "Assert of an specific error",
      "url": "undefined/objects/statsassert"
    },
    {
      "name": "ExpireDateInput",
      "description": "The card expiration date",
      "url": "undefined/inputobjects/expiredateinput"
    },
    {
      "name": "BookRoomInput",
      "description": "Input BookRoom contains list of pax and the room's reference.",
      "url": "undefined/inputobjects/bookroominput"
    },
    {
      "name": "BookPaxInput",
      "description": "Input BookPax contains basic information abaout pax suach as name, surname and age.",
      "url": "undefined/inputobjects/bookpaxinput"
    },
    {
      "name": "MappeaConfirmUploadInput",
      "description": "## ConfirmUpload",
      "url": "undefined/inputobjects/mappeaconfirmuploadinput"
    },
    {
      "name": "UploadFileData",
      "description": "",
      "url": "undefined/objects/uploadfiledata"
    },
    {
      "name": "SupplierDetected",
      "description": "",
      "url": "undefined/objects/supplierdetected"
    },
    {
      "name": "MappeaMapSupplierInput",
      "description": "# MapSupplier",
      "url": "undefined/inputobjects/mappeamapsupplierinput"
    },
    {
      "name": "DefaultSettingsBusinessRulesInput",
      "description": "Input delta price, indicates the price variation permitted by the client before failing the booking.",
      "url": "undefined/inputobjects/defaultsettingsbusinessrulesinput"
    },
    {
      "name": "TimeoutInput",
      "description": "",
      "url": "undefined/inputobjects/timeoutinput"
    },
    {
      "name": "BusinessRules",
      "description": "List of business rules for filtering options based on your interests.",
      "url": "undefined/objects/businessrules"
    },
    {
      "name": "Timeout",
      "description": "",
      "url": "undefined/objects/timeout"
    },
    {
      "name": "fake__color",
      "description": "",
      "url": "undefined/inputobjects/fake__color"
    },
    {
      "name": "fake__options",
      "description": "",
      "url": "undefined/inputobjects/fake__options"
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
