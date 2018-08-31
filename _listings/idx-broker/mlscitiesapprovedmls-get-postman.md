{
  "info": {
    "name": "IDX Broker Get Mls Cities Approved MLS",
    "_postman_id": "a19fbff7-4a79-4fcd-b2b3-4983d70ace19",
    "description": "All cities represented in the current set of MLS data are available from this method.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Approved",
      "item": [
        {
          "id": "2aab33db-46be-455d-b888-37c62964e94d",
          "name": "MlsApprovedmlsGet",
          "request": {
            "url": "http://example.com/mls/approvedmls",
            "method": "GET",
            "header": [
              {
                "key": "accesskey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "ancillarykey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "apiversion",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "outputtype",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "This method provides all of the IDX IDs and names for all of the paperwork approved MLSs on the client's account.\n\nNote: This method was previously camelcased as \"approvedMLS\" but was made lower case to fit the API naming convention. Calls to \"approvedMLS\" will be forwarded to \"approvedmls\" and \"approvedMLS\" is listed as deprecated in the method list."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "17742b6d-c216-4d43-815f-b4fce1c7bb06"
            }
          ]
        }
      ]
    },
    {
      "name": "Mls",
      "item": [
        {
          "id": "73b5d181-cf0d-41b1-8d20-082843fd0c38",
          "name": "MlsAgeByApprovedMLSGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "mls/age/:approvedMLS"
              ],
              "variable": [
                {
                  "id": "approvedMLS",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "accesskey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "ancillarykey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "apiversion",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "outputtype",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "TODO: Add Description"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c8bab205-ebd1-45cf-a2f0-21113163bfee"
            }
          ]
        },
        {
          "id": "2f40abe1-6912-4946-a0b9-16a71e766301",
          "name": "MlsCitiesByApprovedMLSGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "mls/cities/:approvedMLS"
              ],
              "variable": [
                {
                  "id": "approvedMLS",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "accesskey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "ancillarykey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "apiversion",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "outputtype",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "All cities represented in the current set of MLS data are available from this method."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "36a62fa2-f717-4f91-a4f8-06b759eed2f4"
            }
          ]
        },
        {
          "id": "9998aadc-87f2-4d05-8574-8ed56b0395b0",
          "name": "MlsSearchfieldvaluesByApprovedMLSGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "mls/searchfieldvalues/:approvedMLS"
              ],
              "query": [
                {
                  "key": "mlsPtID",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "approvedMLS",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "accesskey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "ancillarykey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "apiversion",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "outputtype",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Field values in a given MLS that are currently allowed to be searched according to MLS guidelines."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "473fe4b8-474d-4de0-aca0-0ffba9710400"
            }
          ]
        },
        {
          "id": "6d0f8dc1-c07b-48e9-b1cc-2e2987432bb0",
          "name": "MlsZipcodesByApprovedMLSGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "mls/zipcodes/:approvedMLS"
              ],
              "variable": [
                {
                  "id": "approvedMLS",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "accesskey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "ancillarykey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "apiversion",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "outputtype",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "All zip codes represented in the current set of MLS data are available from this method."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "47e11c7d-0249-48fd-820e-0ebefce3f86f"
            }
          ]
        },
        {
          "id": "536ed25a-c43f-48c8-b391-e8a71c5b9745",
          "name": "MlsPostalcodesByApprovedMLSGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "mls/postalcodes/:approvedMLS"
              ],
              "variable": [
                {
                  "id": "approvedMLS",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "accesskey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "ancillarykey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "apiversion",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "outputtype",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "All postal codes represented in the current set of MLS data are available from this method."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "321a4cc7-3605-4b7d-97cc-55e4a2cdfc8c"
            }
          ]
        },
        {
          "id": "49c40dbc-a39d-4742-87f5-4fbdf12eacdb",
          "name": "MlsPricesByApprovedMLSGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "mls/prices/:approvedMLS"
              ],
              "variable": [
                {
                  "id": "approvedMLS",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "accesskey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "ancillarykey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "apiversion",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "outputtype",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "The sum total of properties listed in a given MLS as well as sums for each property type in the MLS."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "aa8f64ec-151a-453d-9ff4-fd71b1cd9b9a"
            }
          ]
        },
        {
          "id": "cc94e4c5-4da2-47e9-b526-080a0327d175",
          "name": "MlsPropertycountByApprovedMLSGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "mls/propertycount/:approvedMLS"
              ],
              "query": [
                {
                  "key": "countSpecifier",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "countType",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "approvedMLS",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "accesskey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "ancillarykey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "apiversion",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "outputtype",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gives a total number of listings available for a given city, county, or zipcode"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6a19d32e-c828-4177-8960-6483f745544f"
            }
          ]
        },
        {
          "id": "2228cc71-dff2-4925-bb5b-9de7ad8fde59",
          "name": "MlsPropertytypesByApprovedMLSGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "mls/propertytypes/:approvedMLS"
              ],
              "variable": [
                {
                  "id": "approvedMLS",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "accesskey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "ancillarykey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "apiversion",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "outputtype",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gives the property type information for all types that are available on a given MLS."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2e530182-c474-443d-8d2d-511a4d284144"
            }
          ]
        },
        {
          "id": "1b0c6038-8f26-40b4-a34e-859e3a791386",
          "name": "MlsSearchfieldsByApprovedMLSGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "mls/searchfields/:approvedMLS"
              ],
              "variable": [
                {
                  "id": "approvedMLS",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "accesskey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "ancillarykey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "apiversion",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "outputtype",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "All the fields in a given MLS that are currently allowed to be searched according to MLS guidelines."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "05557d82-97a4-4101-9717-9d62940a2b23"
            }
          ]
        }
      ]
    },
    {
      "name": "List",
      "item": [
        {
          "id": "9b15f8b7-0f82-4413-9300-eb199ca7f1b1",
          "name": "ClientsListallowedfieldsByApprovedMLSAndFeaturedIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "clients/listallowedfields/:approvedMLS/:featuredId"
              ],
              "variable": [
                {
                  "id": "approvedMLS",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "featuredId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "accesskey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "ancillarykey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "apiversion",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "outputtype",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns the allowed returnable fields for a given listingID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "35e7dcd0-2978-4752-b400-8ffa190f77fd"
            }
          ]
        }
      ]
    },
    {
      "name": "Listing",
      "item": [
        {
          "id": "e1663744-a9ac-4bf3-81d6-137fecb9aa19",
          "name": "ClientsListingByApprovedMLSAndFeaturedIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "clients/listing/:approvedMLS/:featuredId"
              ],
              "variable": [
                {
                  "id": "approvedMLS",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "featuredId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "accesskey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "ancillarykey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "apiversion",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "outputtype",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns the detailed information for a given listingID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "302376be-f934-4579-b7d6-bf7b9e83733d"
            }
          ]
        }
      ]
    }
  ]
}