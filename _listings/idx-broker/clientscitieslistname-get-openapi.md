---
swagger: "2.0"
x-collection-name: IDX Broker
x-complete: 0
info:
  title: IDX Broker Get Cities List Name
  description: Returns the IDs and names for each of a client's city lists including
    MLS city lists.
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