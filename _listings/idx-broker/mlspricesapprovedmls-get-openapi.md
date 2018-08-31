---
swagger: "2.0"
x-collection-name: IDX Broker
x-complete: 0
info:
  title: IDX Broker Get Mls Prices Approvedmls
  description: The sum total of properties listed in a given MLS as well as sums for
    each property type in the MLS.
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