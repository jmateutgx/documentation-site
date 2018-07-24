{
  "title": "Boolean",
  "description": "",
  "weight": 1,
  "fields": null,
  "requireby": [
    {
      "name": "AccessData",
      "description": "",
      "url": "undefined/objects/accessdata"
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
      "name": "PageInfo",
      "description": "",
      "url": "undefined/objects/pageinfo"
    },
    {
      "name": "SupplierFilter",
      "description": "",
      "url": "undefined/inputobjects/supplierfilter"
    },
    {
      "name": "ClientFilter",
      "description": "",
      "url": "undefined/inputobjects/clientfilter"
    },
    {
      "name": "ClientData",
      "description": "",
      "url": "undefined/objects/clientdata"
    },
    {
      "name": "OrganizationData",
      "description": "",
      "url": "undefined/objects/organizationdata"
    },
    {
      "name": "GroupCommonData",
      "description": "",
      "url": "undefined/interfaces/groupcommondata"
    },
    {
      "name": "GroupData",
      "description": "",
      "url": "undefined/objects/groupdata"
    },
    {
      "name": "Member",
      "description": "You grant access to members which can be either:\nUsers: A developer, administrator or any other person from your Organization who interacts with the TravelgateX Platform. An email address can be used as the identity of a User.\nService Accounts: An application (Client) instead of an individual User. If you prefer, you can create as many Service Accounts as needed to represent different logical components of your application.",
      "url": "undefined/objects/member"
    },
    {
      "name": "RoleData",
      "description": "",
      "url": "undefined/objects/roledata"
    },
    {
      "name": "ResourceData",
      "description": "",
      "url": "undefined/objects/resourcedata"
    },
    {
      "name": "APIData",
      "description": "",
      "url": "undefined/objects/apidata"
    },
    {
      "name": "HotelData",
      "description": "Hotel data",
      "url": "undefined/objects/hoteldata"
    },
    {
      "name": "DestinationData",
      "description": "Information about destinantion",
      "url": "undefined/objects/destinationdata"
    },
    {
      "name": "HotelSettingsInput",
      "description": "Settings that you can edit for this avail. Values are loaded by default in our Back Office.",
      "url": "undefined/inputobjects/hotelsettingsinput"
    },
    {
      "name": "SettingsBaseInput",
      "description": "Contains the time out and business rules of a supplier or an access.",
      "url": "undefined/inputobjects/settingsbaseinput"
    },
    {
      "name": "Room",
      "description": "Contains the room information of the option returned.",
      "url": "undefined/objects/room"
    },
    {
      "name": "Price",
      "description": "Price indicates the value of the room/option.\nSupplements and/or surcharges can be included into the price, and will be verified with nodes Supplements/Surcharges.",
      "url": "undefined/objects/price"
    },
    {
      "name": "Priceable",
      "description": "",
      "url": "undefined/interfaces/priceable"
    },
    {
      "name": "Markup",
      "description": "Informs markup applied over supplier price.",
      "url": "undefined/objects/markup"
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
      "name": "Surcharge",
      "description": "Surcharge that it can be or it is already added to the option returned. Contains all the information about the surcharge.",
      "url": "undefined/objects/surcharge"
    },
    {
      "name": "CancelPolicy",
      "description": "Information about a policy cancellation.",
      "url": "undefined/objects/cancelpolicy"
    },
    {
      "name": "OperationDetailed",
      "description": "Stats information per operation",
      "url": "undefined/objects/operationdetailed"
    },
    {
      "name": "AccessInput",
      "description": "Access input",
      "url": "undefined/inputobjects/accessinput"
    },
    {
      "name": "CreateClientInput",
      "description": "",
      "url": "undefined/inputobjects/createclientinput"
    },
    {
      "name": "UpdateClientInput",
      "description": "",
      "url": "undefined/inputobjects/updateclientinput"
    },
    {
      "name": "DeltaPriceInput",
      "description": "Input delta price, indicates price variation permitted by the client\nAn error will be returned if the new price does not abide to DeltaPrice. If DeltaPrice is not sent and the integration implements it, we assume that the price range is 0 and the process will continue \n(price is lower or equal to the price showed in valuation).\nThis field is implemented if it’s native to the supplier or if another availability/valuation request needs to be done in Reservation. In case the supplier blocks the option in valuation, reservation \nwill be done automatically in reservation method.",
      "url": "undefined/inputobjects/deltapriceinput"
    },
    {
      "name": "SupplierGroup",
      "description": "group related to a supplier",
      "url": "undefined/objects/suppliergroup"
    },
    {
      "name": "AccessConfigurationInput",
      "description": "The information required to access the supplier's system.",
      "url": "undefined/inputobjects/accessconfigurationinput"
    },
    {
      "name": "AccessConnectUserInput",
      "description": "Connect user input for data access management API",
      "url": "undefined/inputobjects/accessconnectuserinput"
    },
    {
      "name": "ConnectUserGroupInput",
      "description": "group related to a connect user",
      "url": "undefined/inputobjects/connectusergroupinput"
    },
    {
      "name": "AccessSupplierInput",
      "description": "Supplier input for data access management API",
      "url": "undefined/inputobjects/accesssupplierinput"
    },
    {
      "name": "SupplierGroupInput",
      "description": "group related to a supplier",
      "url": "undefined/inputobjects/suppliergroupinput"
    },
    {
      "name": "IdAccessConfigurationInput",
      "description": "",
      "url": "undefined/inputobjects/idaccessconfigurationinput"
    },
    {
      "name": "ConnectUser",
      "description": "Data related to a connected user and its groups",
      "url": "undefined/objects/connectuser"
    },
    {
      "name": "ConnectUserGroup",
      "description": "group related to a connect user",
      "url": "undefined/objects/connectusergroup"
    },
    {
      "name": "MappeaAddOrganizationInput",
      "description": "# AddOrganization",
      "url": "undefined/inputobjects/mappeaaddorganizationinput"
    },
    {
      "name": "MappeaEditOrganizationInput",
      "description": "# EditOrganization",
      "url": "undefined/inputobjects/mappeaeditorganizationinput"
    },
    {
      "name": "fake__options",
      "description": "",
      "url": "undefined/inputobjects/fake__options"
    }
  ],
  "enumValues": null,
  "operator": "scalar",
  "typename": "Boolean",
  "hideGithubLink": true
}
The `Boolean` scalar type represents `true` or `false`.
## GraphQL schema definition

{{% graphql-schema-scalar %}}

## Required by

{{% graphql-require-by %}}
