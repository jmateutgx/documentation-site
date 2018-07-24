{
  "title": "Date",
  "description": "",
  "weight": 1,
  "fields": null,
  "requireby": [
    {
      "name": "HotelCriteriaSearchInput",
      "description": "Search criteria contains destination, travel dates and the number of pax in each room.\nYou must preload the other fields in our system by complete the fields absents.",
      "url": "undefined/inputobjects/hotelcriteriasearchinput"
    },
    {
      "name": "CriteriaSearch",
      "description": "Search criteria contains destination, travel dates and the number of pax in each room.",
      "url": "undefined/objects/criteriasearch"
    },
    {
      "name": "PriceBreakdown",
      "description": "Information about daily price.",
      "url": "undefined/objects/pricebreakdown"
    },
    {
      "name": "RatePlan",
      "description": "Information about the rate of the option returned.",
      "url": "undefined/objects/rateplan"
    },
    {
      "name": "Promotion",
      "description": "Information about room promotions(offers).",
      "url": "undefined/objects/promotion"
    },
    {
      "name": "Supplement",
      "description": "Supplement that it can be or its already added to the option returned. Contains all the information about the supplement.",
      "url": "undefined/objects/supplement"
    },
    {
      "name": "CriteriaBookingDatesInput",
      "description": "Criteria by dates",
      "url": "undefined/inputobjects/criteriabookingdatesinput"
    },
    {
      "name": "BookingHotel",
      "description": "",
      "url": "undefined/objects/bookinghotel"
    },
    {
      "name": "PaymentXBookingInfo",
      "description": "",
      "url": "undefined/objects/paymentxbookinginfo"
    },
    {
      "name": "PaymentXBookingInfoInput",
      "description": "",
      "url": "undefined/inputobjects/paymentxbookinginfoinput"
    }
  ],
  "enumValues": null,
  "operator": "scalar",
  "typename": "Date",
  "hideGithubLink": true
}
The Date type represents Date values. A good example might be a Hotel CheckIn Date.
In queries or mutations, DateTime fields have to be specified in ISO 8601 format with enclosing double quotes: "2017-10-22".
## GraphQL schema definition

{{% graphql-schema-scalar %}}

## Required by

{{% graphql-require-by %}}
