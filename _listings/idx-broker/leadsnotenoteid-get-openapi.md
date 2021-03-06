---
swagger: "2.0"
x-collection-name: IDX Broker
x-complete: 0
info:
  title: IDX Broker Get Leads Not
  description: Get note information for a lead.
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /mls/approvedmls:
    get:
      summary: Get Approved MLS
      description: |-
        This method provides all of the IDX IDs and names for all of the paperwork approved MLSs on the client's account.

        Note: This method was previously camelcased as "approvedMLS" but was made lower case to fit the API naming convention. Calls to "approvedMLS" will be forwarded to "approvedmls" and "approvedMLS" is listed as deprecated in the method list.
      operationId: MlsApprovedmlsGet
      x-api-path-slug: mlsapprovedmls-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Approved
      - MLS
  /mls/age/{approvedMLS}:
    get:
      summary: Get Mls Age Approved MLS
      description: 'TODO: Add Description'
      operationId: MlsAgeByApprovedMLSGet
      x-api-path-slug: mlsageapprovedmls-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: path
        name: approvedMLS
      - in: header
        name: Content-Type
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Mls
      - Age
      - Approved
      - MLS
  /mls/cities/{approvedMLS}:
    get:
      summary: Get Mls Cities Approved MLS
      description: All cities represented in the current set of MLS data are available
        from this method.
      operationId: MlsCitiesByApprovedMLSGet
      x-api-path-slug: mlscitiesapprovedmls-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: path
        name: approvedMLS
      - in: header
        name: Content-Type
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Mls
      - Cities
      - Approved
      - MLS
  /mls/listcomponents:
    get:
      summary: Get Mls List Components
      description: This is a simple, access anywhere, method for getting a list of
        all API components available.
      operationId: MlsListcomponentsGet
      x-api-path-slug: mlslistcomponents-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Mls
      - List
      - Components
  /mls/listmethods:
    get:
      summary: Get Mls Listmethods
      description: A simple method for listing all available methods in the current
        API component. This method will also list which request methods (GET, PUT,
        POST, or DELETE) are supported by each method in addition to each method status.
      operationId: MlsListmethodsGet
      x-api-path-slug: mlslistmethods-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Mls
      - Listmethods
  /mls/postalcodes/{approvedMLS}:
    get:
      summary: Get Mls Addalcodes Approvedmls
      description: All postal codes represented in the current set of MLS data are
        available from this method.
      operationId: MlsPostalcodesByApprovedMLSGet
      x-api-path-slug: mlspostalcodesapprovedmls-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: path
        name: approvedMLS
      - in: header
        name: Content-Type
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Mls
      - Alcodes
      - Approvedmls
  /mls/prices/{approvedMLS}:
    get:
      summary: Get Mls Prices Approvedmls
      description: The sum total of properties listed in a given MLS as well as sums
        for each property type in the MLS.
      operationId: MlsPricesByApprovedMLSGet
      x-api-path-slug: mlspricesapprovedmls-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: path
        name: approvedMLS
      - in: header
        name: Content-Type
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Mls
      - Prices
      - Approvedmls
  /mls/propertycount/{approvedMLS}:
    get:
      summary: Get Mls Propertycount Approvedmls
      description: Gives a total number of listings available for a given city, county,
        or zipcode
      operationId: MlsPropertycountByApprovedMLSGet
      x-api-path-slug: mlspropertycountapprovedmls-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: path
        name: approvedMLS
      - in: header
        name: Content-Type
      - in: query
        name: countSpecifier
      - in: query
        name: countType
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Mls
      - Propertycount
      - Approvedmls
  /mls/propertytypes/{approvedMLS}:
    get:
      summary: Get Mls Propertytypes Approvedmls
      description: Gives the property type information for all types that are available
        on a given MLS.
      operationId: MlsPropertytypesByApprovedMLSGet
      x-api-path-slug: mlspropertytypesapprovedmls-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: path
        name: approvedMLS
      - in: header
        name: Content-Type
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Mls
      - Propertytypes
      - Approvedmls
  /mls/searchfields/{approvedMLS}:
    get:
      summary: Get Mls Searchfields Approvedmls
      description: All the fields in a given MLS that are currently allowed to be
        searched according to MLS guidelines.
      operationId: MlsSearchfieldsByApprovedMLSGet
      x-api-path-slug: mlssearchfieldsapprovedmls-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: path
        name: approvedMLS
      - in: header
        name: Content-Type
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Mls
      - Searchfields
      - Approvedmls
  /mls/searchfieldvalues/{approvedMLS}:
    get:
      summary: Get Mls Search Field Values Approved MLS
      description: Field values in a given MLS that are currently allowed to be searched
        according to MLS guidelines.
      operationId: MlsSearchfieldvaluesByApprovedMLSGet
      x-api-path-slug: mlssearchfieldvaluesapprovedmls-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: path
        name: approvedMLS
      - in: header
        name: Content-Type
      - in: query
        name: mlsPtID
      - in: query
        name: name
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Mls
      - Search
      - Field
      - Values
      - Approved
      - MLS
  /mls/zipcodes/{approvedMLS}:
    get:
      summary: Get Mls Zipcodes Approved MLS
      description: All zip codes represented in the current set of MLS data are available
        from this method.
      operationId: MlsZipcodesByApprovedMLSGet
      x-api-path-slug: mlszipcodesapprovedmls-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: path
        name: approvedMLS
      - in: header
        name: Content-Type
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Mls
      - Zipcodes
      - Approved
      - MLS
  /clients/agents:
    get:
      summary: Get Agents
      description: View agent information on a multi-user account.
      operationId: ClientsAgentsGet
      x-api-path-slug: clientsagents-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Agents
  /clients/apiversion:
    get:
      summary: Get Apiversion
      description: Get the default api version.
      operationId: ClientsApiversionGet
      x-api-path-slug: clientsapiversion-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Apiversion
  /clients/cities:
    get:
      summary: Get Cities
      description: Returns the cities available in each of a client's city lists.
      operationId: ClientsCitiesGet
      x-api-path-slug: clientscities-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Cities
  /clients/citieslistname:
    get:
      summary: Get Cities List Name
      description: Returns the IDs and names for each of a client's city lists including
        MLS city lists.
      operationId: ClientsCitieslistnameGet
      x-api-path-slug: clientscitieslistname-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Cities
      - List
      - Name
  /clients/counties:
    get:
      summary: Get Counties
      description: Returns the counties available in each of a client's county lists.
      operationId: ClientsCountiesGet
      x-api-path-slug: clientscounties-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Counties
  /clients/countieslistname:
    get:
      summary: Get Countieslistname
      description: Returns the IDs and names for each of a client's counties lists
        including MLS counties lists.
      operationId: ClientsCountieslistnameGet
      x-api-path-slug: clientscountieslistname-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Countieslistname
  /clients/dynamicwrapperurl:
    post:
      summary: Post Dynamicwrapperurl
      description: Set wrapper URL. This is the global url.
      operationId: ClientsDynamicwrapperurlPost
      x-api-path-slug: clientsdynamicwrapperurl-post
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: formData
        name: dynamicURL
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Dynamicwrapperurl
  /clients/featured:
    get:
      summary: Get Featured
      description: Returns a basic set of information for all of the client's featured
        (active) properties
      operationId: ClientsFeaturedGet
      x-api-path-slug: clientsfeatured-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Featured
  /clients/listallowedfields/{approvedMLS}/{featuredId}:
    get:
      summary: Get List Allowed Fields Approved MLS Featured
      description: Returns the allowed returnable fields for a given listingID.
      operationId: ClientsListallowedfieldsByApprovedMLSAndFeaturedIdGet
      x-api-path-slug: clientslistallowedfieldsapprovedmlsfeaturedid-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: path
        name: approvedMLS
      - in: header
        name: Content-Type
      - in: path
        name: featuredId
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - List
      - Owed
      - Fields
      - Approved
      - MLS
      - Featured
  /clients/listcomponents:
    get:
      summary: Get Listcomponents
      description: This is a simple, access anywhere, method for getting a list of
        all API components available.
      operationId: ClientsListcomponentsGet
      x-api-path-slug: clientslistcomponents-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Listcomponents
  /clients/listing/{approvedMLS}/{featuredId}:
    get:
      summary: Get Listing Approved MLS Featuredid
      description: Returns the detailed information for a given listingID.
      operationId: ClientsListingByApprovedMLSAndFeaturedIdGet
      x-api-path-slug: clientslistingapprovedmlsfeaturedid-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: path
        name: approvedMLS
      - in: header
        name: Content-Type
      - in: path
        name: featuredId
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Listing
      - Approved
      - MLS
      - Featuredid
  /clients/listmethods:
    get:
      summary: Get List Methods
      description: A simple method for listing all available methods in the current
        API component.
      operationId: ClientsListmethodsGet
      x-api-path-slug: clientslistmethods-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - List
      - Methods
  /clients/offices:
    get:
      summary: Get Offices
      description: View all offices on a mutli-user account.
      operationId: ClientsOfficesGet
      x-api-path-slug: clientsoffices-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Offices
  /clients/postalcodes:
    get:
      summary: Get Addalcodes
      description: Returns the postalcodes available in each of a client's postalcode
        lists.
      operationId: ClientsPostalcodesGet
      x-api-path-slug: clientspostalcodes-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Alcodes
  /clients/postalcodeslistname:
    get:
      summary: Get Addalcodeslistname
      description: Returns the IDs and names for each of a client's postalcode lists
        including MLS postalcode lists.
      operationId: ClientsPostalcodeslistnameGet
      x-api-path-slug: clientspostalcodeslistname-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Alcodeslistname
  /clients/savedlinks:
    get:
      summary: Get Saved Link
      description: Getclient saved links
      operationId: ClientsSavedlinksGet
      x-api-path-slug: clientssavedlinks-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Saved
      - Link
    put:
      summary: Put Saved Link
      description: Create a new client saved link
      operationId: ClientsSavedlinksPut
      x-api-path-slug: clientssavedlinks-put
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: formData
        name: linkName
      - in: formData
        name: linkTitle
      - in: header
        name: outputtype
      - in: formData
        name: pageTitle
      - in: formData
        name: queryString[hp]
      - in: formData
        name: queryString[idxID]
      responses:
        200:
          description: OK
      tags:
      - Saved
      - Link
  /clients/properties/{savedLinkId}:
    get:
      summary: Get Properties Saved Link
      description: Get client saved links results
      operationId: ClientsPropertiesBySavedLinkIdGet
      x-api-path-slug: clientspropertiessavedlinkid-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: header
        name: outputtype
      - in: path
        name: savedLinkId
      responses:
        200:
          description: OK
      tags:
      - Properties
      - Saved
      - Link
  /clients/savedlinks/{savedLinkId}:
    post:
      summary: Post Saved Link Saved Link
      description: Update a client saved link
      operationId: ClientsSavedlinksBySavedLinkIdPost
      x-api-path-slug: clientssavedlinkssavedlinkid-post
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: formData
        name: linkName
      - in: formData
        name: linkTitle
      - in: header
        name: outputtype
      - in: formData
        name: pageTitle
      - in: formData
        name: queryString[hp]
      - in: formData
        name: queryString[idxID]
      - in: path
        name: savedLinkId
      responses:
        200:
          description: OK
      tags:
      - Saved
      - Link
      - Saved
      - Link
    delete:
      summary: Delete Saved Link Saved Link
      description: Delete a client saved link
      operationId: ClientsSavedlinksBySavedLinkIdDelete
      x-api-path-slug: clientssavedlinkssavedlinkid-delete
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: formData
        name: linkName
      - in: formData
        name: linkTitle
      - in: header
        name: outputtype
      - in: formData
        name: pageTitle
      - in: formData
        name: queryString[hp]
      - in: formData
        name: queryString[idxID]
      - in: path
        name: savedLinkId
      responses:
        200:
          description: OK
      tags:
      - Saved
      - Link
      - Saved
      - Link
  /clients/searchquery:
    get:
      summary: Get Search Query
      description: Performs search and returns the results.
      operationId: ClientsSearchqueryGet
      x-api-path-slug: clientssearchquery-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Search
      - Query
  /clients/soldpending:
    get:
      summary: Get Sold Pending
      description: Returns a basic set of information for all of the client's sold
        and pending properties.
      operationId: ClientsSoldpendingGet
      x-api-path-slug: clientssoldpending-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Sold
      - Pending
  /clients/supplemental:
    get:
      summary: Get Supplemental
      description: Get supplemental listings.
      operationId: ClientsSupplementalGet
      x-api-path-slug: clientssupplemental-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Supplemental
    put:
      summary: Put Supplemental
      description: Create a new supplemental listing.
      operationId: ClientsSupplementalPut
      x-api-path-slug: clientssupplemental-put
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: formData
        name: images[hp]
      - in: formData
        name: likeIdxID
      - in: formData
        name: likeMlsPtID
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Supplemental
  /clients/supplemental/{suppId}:
    post:
      summary: Post Supplemental
      description: Update a supplemental listing.
      operationId: ClientsSupplementalBySuppIdPost
      x-api-path-slug: clientssupplementalsuppid-post
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: formData
        name: images[hp]
      - in: formData
        name: likeIdxID
      - in: formData
        name: likeMlsPtID
      - in: header
        name: outputtype
      - in: path
        name: suppId
      responses:
        200:
          description: OK
      tags:
      - Supplemental
    delete:
      summary: Delete Supplemental
      description: Delete a supplemental listing.
      operationId: ClientsSupplementalBySuppIdDelete
      x-api-path-slug: clientssupplementalsuppid-delete
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: header
        name: outputtype
      - in: path
        name: suppId
      responses:
        200:
          description: OK
      tags:
      - Supplemental
  /clients/systemlinks:
    get:
      summary: Get System Links
      description: Gathers all the pages system pages (search, featured, contact,
        etc) that can be directly linked to without additional property information
        being included in the URL.
      operationId: ClientsSystemlinksGet
      x-api-path-slug: clientssystemlinks-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - System
      - Links
  /clients/widgetsrc:
    get:
      summary: Get Wgetsrc
      description: Gather all the URLs for javascript widgets on the user's account.
        These widgets can then be placed on the user's main site via the included
        URLs.
      operationId: ClientsWidgetsrcGet
      x-api-path-slug: clientswidgetsrc-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Wgetsrc
  /clients/wrappercache:
    delete:
      summary: Delete Wrapper Cache
      description: Delete wrapper cache.
      operationId: ClientsWrappercacheDelete
      x-api-path-slug: clientswrappercache-delete
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Wrapper
      - Cache
  /clients/zipcodes:
    get:
      summary: Get Zipcodes
      description: Returns the zipcodes available in each of a client's zipcode lists.
      operationId: ClientsZipcodesGet
      x-api-path-slug: clientszipcodes-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Zipcodes
  /leads/lead:
    get:
      summary: Get Leads Lead
      description: |-
        Get information for one or multiple leads.

        Example Request: https://api.idxbroker.com/leads/lead?interval=24&startDatetime=2016-01-01+23:59:59&dateType=subscribeDate

        For Data on a specific lead add/LEAD_ID_HERE

        Example: https://api.idxbroker.com/leads/lead/123
      operationId: LeadsLeadGet
      x-api-path-slug: leadslead-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Leads
      - Lead
    put:
      summary: Put Leads Lead
      description: |-
        Get information for one or multiple leads.

        Example Request: https://api.idxbroker.com/leads/lead?interval=24&startDatetime=2016-01-01+23:59:59&dateType=subscribeDate

        For Data on a specific lead add/LEAD_ID_HERE

        Example: https://api.idxbroker.com/leads/lead/123
      operationId: LeadsLeadPut
      x-api-path-slug: leadslead-put
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: formData
        name: email
      - in: formData
        name: firstName
      - in: formData
        name: lastName
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Leads
      - Lead
  /leads/lead/{leadId}:
    post:
      summary: Post Leads Lead Lead
      description: |-
        Post information for a lead.


        Example: https://api.idxbroker.com/leads/lead/123
      operationId: LeadsLeadByLeadIdPost
      x-api-path-slug: leadsleadleadid-post
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: formData
        name: email
      - in: formData
        name: firstName
      - in: formData
        name: lastName
      - in: path
        name: leadId
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Leads
      - Lead
      - Lead
    delete:
      summary: Delete Leads Lead Lead
      description: |-
        Delete Lead

        Example: https://api.idxbroker.com/leads/lead/123
      operationId: LeadsLeadByLeadIdDelete
      x-api-path-slug: leadsleadleadid-delete
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: path
        name: leadId
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Leads
      - Lead
      - Lead
  /leads/note/{leadId}:
    put:
      summary: Put Leads Note
      description: Add new note information for a lead.
      operationId: LeadsNoteByLeadIdPut
      x-api-path-slug: leadsnoteleadid-put
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: path
        name: leadId
      - in: formData
        name: note
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Leads
      - Note
  /leads/note/{noteId}:
    get:
      summary: Get Leads Not
      description: Get note information for a lead.
      operationId: LeadsNoteByNoteIdGet
      x-api-path-slug: leadsnotenoteid-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: path
        name: noteId
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Leads
      - Not
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---