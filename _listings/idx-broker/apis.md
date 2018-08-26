---
name: IDX Broker
x-slug: idx-broker
description: Based in Eugene, OR, IDX, LLC is nationally known as a leading provider
  of real estate search applications. IDX, LLC actively manages more than $2 trillion
  worth of active listing data from more than 600 individual Multiple Listings Services
  (MLS). IDX, LLC provides integrated IDX software, customizable listing search utilities
  and lead management tools for real estate based websites (IDX Broker).
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
x-kinRank: "7"
x-alexaRank: "0"
tags: IDX Broker
created: "2018-08-26"
modified: "2018-08-26"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/apis.md
specificationVersion: "0.14"
apis:
- name: IDX API 1.4.0 Test Runner - Get Approved MLS
  x-api-slug: mlsapprovedmls-get
  description: |-
    This method provides all of the IDX IDs and names for all of the paperwork approved MLSs on the client's account.

    Note: This method was previously camelcased as "approvedMLS" but was made lower case to fit the API naming convention. Calls to "approvedMLS" will be forwarded to "approvedmls" and "approvedMLS" is listed as deprecated in the method list.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/mlsapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/mlsapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Age Approved MLS
  x-api-slug: mlsageapprovedmls-get
  description: 'TODO: Add Description'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/mlsageapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/mlsageapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Cities Approved MLS
  x-api-slug: mlscitiesapprovedmls-get
  description: All cities represented in the current set of MLS data are available
    from this method.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/mlscitiesapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/mlscitiesapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls List Components
  x-api-slug: mlslistcomponents-get
  description: This is a simple, access anywhere, method for getting a list of all
    API components available.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/mlslistcomponents-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/mlslistcomponents-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Listmethods
  x-api-slug: mlslistmethods-get
  description: A simple method for listing all available methods in the current API
    component. This method will also list which request methods (GET, PUT, POST, or
    DELETE) are supported by each method in addition to each method status.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/mlslistmethods-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/mlslistmethods-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Addalcodes Approvedmls
  x-api-slug: mlspostalcodesapprovedmls-get
  description: All postal codes represented in the current set of MLS data are available
    from this method.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/mlspostalcodesapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/mlspostalcodesapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Prices Approvedmls
  x-api-slug: mlspricesapprovedmls-get
  description: The sum total of properties listed in a given MLS as well as sums for
    each property type in the MLS.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/mlspricesapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/mlspricesapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Propertycount Approvedmls
  x-api-slug: mlspropertycountapprovedmls-get
  description: Gives a total number of listings available for a given city, county,
    or zipcode
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/mlspropertycountapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/mlspropertycountapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Propertytypes Approvedmls
  x-api-slug: mlspropertytypesapprovedmls-get
  description: Gives the property type information for all types that are available
    on a given MLS.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/mlspropertytypesapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/mlspropertytypesapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Searchfields Approvedmls
  x-api-slug: mlssearchfieldsapprovedmls-get
  description: All the fields in a given MLS that are currently allowed to be searched
    according to MLS guidelines.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/mlssearchfieldsapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/mlssearchfieldsapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Search Field Values Approved MLS
  x-api-slug: mlssearchfieldvaluesapprovedmls-get
  description: Field values in a given MLS that are currently allowed to be searched
    according to MLS guidelines.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/mlssearchfieldvaluesapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/mlssearchfieldvaluesapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Zipcodes Approved MLS
  x-api-slug: mlszipcodesapprovedmls-get
  description: All zip codes represented in the current set of MLS data are available
    from this method.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/mlszipcodesapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/mlszipcodesapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Agents
  x-api-slug: clientsagents-get
  description: View agent information on a multi-user account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientsagents-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientsagents-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Apiversion
  x-api-slug: clientsapiversion-get
  description: Get the default api version.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientsapiversion-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientsapiversion-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Cities
  x-api-slug: clientscities-get
  description: Returns the cities available in each of a client's city lists.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientscities-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientscities-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Cities List Name
  x-api-slug: clientscitieslistname-get
  description: Returns the IDs and names for each of a client's city lists including
    MLS city lists.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientscitieslistname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientscitieslistname-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Counties
  x-api-slug: clientscounties-get
  description: Returns the counties available in each of a client's county lists.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientscounties-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientscounties-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Countieslistname
  x-api-slug: clientscountieslistname-get
  description: Returns the IDs and names for each of a client's counties lists including
    MLS counties lists.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientscountieslistname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientscountieslistname-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Post Dynamicwrapperurl
  x-api-slug: clientsdynamicwrapperurl-post
  description: Set wrapper URL. This is the global url.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientsdynamicwrapperurl-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientsdynamicwrapperurl-post-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Featured
  x-api-slug: clientsfeatured-get
  description: Returns a basic set of information for all of the client's featured
    (active) properties
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientsfeatured-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientsfeatured-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get List Allowed Fields Approved MLS Featured
  x-api-slug: clientslistallowedfieldsapprovedmlsfeaturedid-get
  description: Returns the allowed returnable fields for a given listingID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientslistallowedfieldsapprovedmlsfeaturedid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientslistallowedfieldsapprovedmlsfeaturedid-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Listcomponents
  x-api-slug: clientslistcomponents-get
  description: This is a simple, access anywhere, method for getting a list of all
    API components available.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientslistcomponents-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientslistcomponents-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Listing Approved MLS Featuredid
  x-api-slug: clientslistingapprovedmlsfeaturedid-get
  description: Returns the detailed information for a given listingID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientslistingapprovedmlsfeaturedid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientslistingapprovedmlsfeaturedid-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get List Methods
  x-api-slug: clientslistmethods-get
  description: A simple method for listing all available methods in the current API
    component.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientslistmethods-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientslistmethods-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Offices
  x-api-slug: clientsoffices-get
  description: View all offices on a mutli-user account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientsoffices-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientsoffices-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Addalcodes
  x-api-slug: clientspostalcodes-get
  description: Returns the postalcodes available in each of a client's postalcode
    lists.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientspostalcodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientspostalcodes-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Addalcodeslistname
  x-api-slug: clientspostalcodeslistname-get
  description: Returns the IDs and names for each of a client's postalcode lists including
    MLS postalcode lists.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientspostalcodeslistname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientspostalcodeslistname-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Saved Link
  x-api-slug: clientssavedlinks-get
  description: Getclient saved links
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientssavedlinks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientssavedlinks-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Put Saved Link
  x-api-slug: clientssavedlinks-put
  description: Create a new client saved link
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientssavedlinks-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientssavedlinks-put-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Properties Saved Link
  x-api-slug: clientspropertiessavedlinkid-get
  description: Get client saved links results
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientspropertiessavedlinkid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientspropertiessavedlinkid-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Post Saved Link Saved Link
  x-api-slug: clientssavedlinkssavedlinkid-post
  description: Update a client saved link
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientssavedlinkssavedlinkid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientssavedlinkssavedlinkid-post-openapi.md
- name: IDX API 1.4.0 Test Runner - Delete Saved Link Saved Link
  x-api-slug: clientssavedlinkssavedlinkid-delete
  description: Delete a client saved link
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientssavedlinkssavedlinkid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientssavedlinkssavedlinkid-delete-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Search Query
  x-api-slug: clientssearchquery-get
  description: Performs search and returns the results.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientssearchquery-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientssearchquery-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Sold Pending
  x-api-slug: clientssoldpending-get
  description: Returns a basic set of information for all of the client's sold and
    pending properties.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientssoldpending-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientssoldpending-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Supplemental
  x-api-slug: clientssupplemental-get
  description: Get supplemental listings.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientssupplemental-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientssupplemental-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Put Supplemental
  x-api-slug: clientssupplemental-put
  description: Create a new supplemental listing.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientssupplemental-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientssupplemental-put-openapi.md
- name: IDX API 1.4.0 Test Runner - Post Supplemental
  x-api-slug: clientssupplementalsuppid-post
  description: Update a supplemental listing.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientssupplementalsuppid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientssupplementalsuppid-post-openapi.md
- name: IDX API 1.4.0 Test Runner - Delete Supplemental
  x-api-slug: clientssupplementalsuppid-delete
  description: Delete a supplemental listing.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientssupplementalsuppid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientssupplementalsuppid-delete-openapi.md
- name: IDX API 1.4.0 Test Runner - Get System Links
  x-api-slug: clientssystemlinks-get
  description: Gathers all the pages system pages (search, featured, contact, etc)
    that can be directly linked to without additional property information being included
    in the URL.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientssystemlinks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientssystemlinks-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Wgetsrc
  x-api-slug: clientswidgetsrc-get
  description: Gather all the URLs for javascript widgets on the user's account. These
    widgets can then be placed on the user's main site via the included URLs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientswidgetsrc-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientswidgetsrc-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Delete Wrapper Cache
  x-api-slug: clientswrappercache-delete
  description: Delete wrapper cache.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientswrappercache-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientswrappercache-delete-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Zipcodes
  x-api-slug: clientszipcodes-get
  description: Returns the zipcodes available in each of a client's zipcode lists.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientszipcodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/clientszipcodes-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Leads Lead
  x-api-slug: leadslead-get
  description: |-
    Get information for one or multiple leads.

    Example Request: https://api.idxbroker.com/leads/lead?interval=24&startDatetime=2016-01-01+23:59:59&dateType=subscribeDate

    For Data on a specific lead add/LEAD_ID_HERE

    Example: https://api.idxbroker.com/leads/lead/123
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/leadslead-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/leadslead-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Put Leads Lead
  x-api-slug: leadslead-put
  description: |-
    Get information for one or multiple leads.

    Example Request: https://api.idxbroker.com/leads/lead?interval=24&startDatetime=2016-01-01+23:59:59&dateType=subscribeDate

    For Data on a specific lead add/LEAD_ID_HERE

    Example: https://api.idxbroker.com/leads/lead/123
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/leadslead-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/leadslead-put-openapi.md
- name: IDX API 1.4.0 Test Runner - Post Leads Lead Lead
  x-api-slug: leadsleadleadid-post
  description: |-
    Post information for a lead.


    Example: https://api.idxbroker.com/leads/lead/123
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/leadsleadleadid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/leadsleadleadid-post-openapi.md
- name: IDX API 1.4.0 Test Runner - Delete Leads Lead Lead
  x-api-slug: leadsleadleadid-delete
  description: |-
    Delete Lead

    Example: https://api.idxbroker.com/leads/lead/123
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/leadsleadleadid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/leadsleadleadid-delete-openapi.md
- name: IDX API 1.4.0 Test Runner - Put Leads Note
  x-api-slug: leadsnoteleadid-put
  description: Add new note information for a lead.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/leadsnoteleadid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/leadsnoteleadid-put-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Leads Not
  x-api-slug: leadsnotenoteid-get
  description: Get note information for a lead.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/leadsnotenoteid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/leadsnotenoteid-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Post Leads Note
  x-api-slug: leadsnoteleadidnoteid-post
  description: Post new note information for a lead.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/leadsnoteleadidnoteid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/leadsnoteleadidnoteid-post-openapi.md
- name: IDX API 1.4.0 Test Runner - Delete Leads Note
  x-api-slug: leadsnoteleadidnoteid-delete
  description: Delete note information for a lead.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/leadsnoteleadidnoteid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/leadsnoteleadidnoteid-delete-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Leads Property
  x-api-slug: leadspropertyleadid-get
  description: Get a property information for a lead.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/leadspropertyleadid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/leadspropertyleadid-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Put Leads Property
  x-api-slug: leadspropertyleadid-put
  description: Add new property information for a lead.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/leadspropertyleadid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/leadspropertyleadid-put-openapi.md
- name: IDX API 1.4.0 Test Runner - Post Leads Property
  x-api-slug: leadspropertyleadidpropid-post
  description: Update a property information for a lead.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/leadspropertyleadidpropid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/leadspropertyleadidpropid-post-openapi.md
- name: IDX API 1.4.0 Test Runner - Delete Leads Property
  x-api-slug: leadspropertyleadidpropid-delete
  description: Delete a property information for a lead.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/leadspropertyleadidpropid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/leadspropertyleadidpropid-delete-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Leads Search
  x-api-slug: leadssearchleadid-get
  description: Get saved search information for a lead.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/leadssearchleadid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/leadssearchleadid-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Put Leads Search
  x-api-slug: leadssearchleadid-put
  description: New search information for a lead.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/leadssearchleadid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/leadssearchleadid-put-openapi.md
- name: IDX API 1.4.0 Test Runner - Post Leads Search
  x-api-slug: leadssearchleadidsearchid-post
  description: Update search information for a lead.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/leadssearchleadidsearchid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/leadssearchleadidsearchid-post-openapi.md
- name: IDX API 1.4.0 Test Runner - Delete Leads Search
  x-api-slug: leadssearchleadidsearchid-delete
  description: Delete search information for a lead.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/leadssearchleadidsearchid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/leadssearchleadidsearchid-delete-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Leads Lead Traffic
  x-api-slug: leadsleadtrafficleadid-get
  description: Get information on a lead's traffic history.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/leadsleadtrafficleadid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/leadsleadtrafficleadid-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Leads List Components
  x-api-slug: leadslistcomponents-get
  description: This is a simple, access anywhere, method for getting a list of all
    API components available.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/leadslistcomponents-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/leadslistcomponents-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Leads List Methods
  x-api-slug: leadslistmethods-get
  description: A simple method for listing all available methods in the current API
    component.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/leadslistmethods-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/leadslistmethods-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Partners Aggregated Agents
  x-api-slug: partnersaggregatedagents-get
  description: Get a list of all agents for your clients.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/partnersaggregatedagents-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/partnersaggregatedagents-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Partners Aggregated Featured
  x-api-slug: partnersaggregatedfeatured-get
  description: Get a list of featured MLS properties.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/partnersaggregatedfeatured-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/partnersaggregatedfeatured-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Partners Aggregated Leads
  x-api-slug: partnersaggregatedleads-get
  description: Get a list of all leads.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/partnersaggregatedleads-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/partnersaggregatedleads-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Partners Aggregated Lead Traffic
  x-api-slug: partnersaggregatedleadtraffic-get
  description: Get a list of all leads traffic history.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/partnersaggregatedleadtraffic-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/partnersaggregatedleadtraffic-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Partners Aggregated Listing Status
  x-api-slug: partnersaggregatedlistingstatus-get
  description: This method gives the status for all MLS listings (not supplemental)
    broken down by client account ID. This includes sold/pending listings with an
    unknown status which are not usually returned by sold/pending api methods. This
    is helpful if you need to know when previously gathered featured properties have
    left the market.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/partnersaggregatedlistingstatus-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/partnersaggregatedlistingstatus-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Partners Aggregated Properties
  x-api-slug: partnersaggregatedproperties-get
  description: Get a list of all lead saved properties.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/partnersaggregatedproperties-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/partnersaggregatedproperties-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Partners Aggregated Searches
  x-api-slug: partnersaggregatedsearches-get
  description: Get a list of all lead saved searches.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/partnersaggregatedsearches-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/partnersaggregatedsearches-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Partners Aggregated Sold Pending
  x-api-slug: partnersaggregatedsoldpending-get
  description: Get a list of sold/pending MLS properties.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/partnersaggregatedsoldpending-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/partnersaggregatedsoldpending-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Partners Aggregated Supplemental
  x-api-slug: partnersaggregatedsupplemental-get
  description: Get a list of supplemental (non-MLS) properties.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/partnersaggregatedsupplemental-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/partnersaggregatedsupplemental-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Partners Clients
  x-api-slug: partnersclients-get
  description: A list of clients available to a given partner. The list of clients
    can be filtered by GET values.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/partnersclients-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/partnersclients-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Partners List Components
  x-api-slug: partnerslistcomponents-get
  description: This is a simple, access anywhere, method for getting a list of all
    API components available.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/partnerslistcomponents-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/partnerslistcomponents-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Partners List Methods
  x-api-slug: partnerslistmethods-get
  description: A simple method for listing all available methods in the current API
    component.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/partnerslistmethods-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/partnerslistmethods-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Partners Property Types
  x-api-slug: partnerspropertytypes-get
  description: Gives the names and IDs of all available property types. This method
    differs from the property type lookup method in the client API component in that
    it can look up property types for any active Platinum MLS, not just those for
    which the client is a member.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/partnerspropertytypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/idx-broker/master/_listings/idx-broker/partnerspropertytypes-get-openapi.md
x-common:
- type: x-blog
  url: https://blog.idxbroker.com/
- type: x-blog-rss
  url: https://blog.idxbroker.com/feed/
- type: x-website
  url: http://www.idxbroker.com
- type: x-api-gallery
  url: http://iconfinder.api.gallery.streamdata.io
- type: x-api-stack
  url: http://idx.broker.stack.network
- type: x-developer
  url: https://developers.idxbroker.com/
- type: x-forum
  url: https://developers.idxbroker.com/forums-home/
- type: x-getting-started
  url: https://developers.idxbroker.com/getting-started/
- type: x-partners
  url: https://developers.idxbroker.com/partnership/
- type: x-twitter
  url: https://twitter.com/idxbroker
- type: x-website
  url: http://www.idxbroker.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---