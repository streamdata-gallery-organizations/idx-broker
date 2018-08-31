{
  "info": {
    "name": "IDX Broker Get Wgetsrc",
    "_postman_id": "ee7b9f20-f8ce-4f13-9222-8a38da449522",
    "description": "Gather all the URLs for javascript widgets on the user's account. These widgets can then be placed on the user's main site via the included URLs.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Approved",
      "item": [
        {
          "id": "97b4a271-b423-4e22-a071-70d214490749",
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
              "id": "1540b713-dbad-407f-96cc-dcfe465f5dfb"
            }
          ]
        }
      ]
    },
    {
      "name": "Mls",
      "item": [
        {
          "id": "be4b7cc2-00cd-4965-8073-6d58abe39284",
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
              "id": "e7e86cc6-7ef0-4e3b-be08-da23df5a560c"
            }
          ]
        },
        {
          "id": "1b780578-e34d-4c1f-bee6-4b284a4ae1bf",
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
              "id": "cebae3a3-5669-4da5-b9d3-ecde5ce2d40a"
            }
          ]
        },
        {
          "id": "5959470e-4413-4fa5-83e4-00cb8f82b162",
          "name": "MlsListcomponentsGet",
          "request": {
            "url": "http://example.com/mls/listcomponents",
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
            "description": "This is a simple, access anywhere, method for getting a list of all API components available."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "71e93ba6-ee26-4444-bfa1-7e7af4d92d02"
            }
          ]
        },
        {
          "id": "414de47f-0f6d-4f7c-98a3-db1a52c2b295",
          "name": "MlsListmethodsGet",
          "request": {
            "url": "http://example.com/mls/listmethods",
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
            "description": "A simple method for listing all available methods in the current API component. This method will also list which request methods (GET, PUT, POST, or DELETE) are supported by each method in addition to each method status."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d724c935-7b71-497e-bd2c-5d32cdf9063e"
            }
          ]
        },
        {
          "id": "0fc2c663-e924-42c5-b9c7-9ab0ea2933c8",
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
              "id": "676a1560-ebdf-463b-83ec-56ae6a333c7a"
            }
          ]
        },
        {
          "id": "72d32683-a4e2-4d9b-a468-221dab2f5251",
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
              "id": "a07938ab-d234-4a74-934c-1ced5526939c"
            }
          ]
        },
        {
          "id": "653c9550-be7e-41a0-9aeb-9e5ad4bb7de1",
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
              "id": "bdf1e6e9-107e-4975-a3af-e041419ca5f5"
            }
          ]
        },
        {
          "id": "4d28ddf7-e692-4b71-9a4e-81032541c924",
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
              "id": "1025a83c-4502-47b2-8023-d012ea9a087f"
            }
          ]
        },
        {
          "id": "8b549105-3143-4881-943f-7f840c4c7a81",
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
              "id": "f5672d91-d9c3-414e-8c23-c341ade16d81"
            }
          ]
        },
        {
          "id": "39e9a7ff-092f-4c2e-b142-c793a11f96f2",
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
              "id": "efa6fe40-1a43-4855-ac86-b76ec8ce38c8"
            }
          ]
        },
        {
          "id": "cc6220d8-aa16-451e-91c0-5aaea2976143",
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
              "id": "1732bddd-4a37-4140-9d5d-b598e714aff3"
            }
          ]
        }
      ]
    },
    {
      "name": "Agents",
      "item": [
        {
          "id": "0dbd416d-186f-4ff5-8882-113af3df59da",
          "name": "ClientsAgentsGet",
          "request": {
            "url": "http://example.com/clients/agents",
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
            "description": "View agent information on a multi-user account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9d444e98-d94b-4d0a-9b8d-31e76f228623"
            }
          ]
        }
      ]
    },
    {
      "name": "Apiversion",
      "item": [
        {
          "id": "429f8ce8-36d3-4df7-aa1e-37d5bc6359c6",
          "name": "ClientsApiversionGet",
          "request": {
            "url": "http://example.com/clients/apiversion",
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
            "description": "Get the default api version."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2aea2ce7-0044-4ac9-8d71-764db434a45f"
            }
          ]
        }
      ]
    },
    {
      "name": "Cities",
      "item": [
        {
          "id": "92a7f452-174f-476a-a5b5-57ca623ca057",
          "name": "ClientsCitiesGet",
          "request": {
            "url": "http://example.com/clients/cities",
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
            "description": "Returns the cities available in each of a client's city lists."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "23aa5b69-c38e-4a11-b002-cab8c3c1bef3"
            }
          ]
        },
        {
          "id": "2acec201-071e-42b3-a837-9e2080b6f677",
          "name": "ClientsCitieslistnameGet",
          "request": {
            "url": "http://example.com/clients/citieslistname",
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
            "description": "Returns the IDs and names for each of a client's city lists including MLS city lists."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0072cc66-1ba3-4779-997e-4c36f4d7b8d0"
            }
          ]
        }
      ]
    },
    {
      "name": "Counties",
      "item": [
        {
          "id": "a9f49123-6cdc-418d-8e54-9b0733b8c886",
          "name": "ClientsCountiesGet",
          "request": {
            "url": "http://example.com/clients/counties",
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
            "description": "Returns the counties available in each of a client's county lists."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "428bdb57-f9e4-41d4-87b8-c9fc3a90540f"
            }
          ]
        }
      ]
    },
    {
      "name": "Countieslistname",
      "item": [
        {
          "id": "8564d319-0dd1-43a2-8efe-81fd25f9c2d0",
          "name": "ClientsCountieslistnameGet",
          "request": {
            "url": "http://example.com/clients/countieslistname",
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
            "description": "Returns the IDs and names for each of a client's counties lists including MLS counties lists."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "df569c0c-ade4-4767-8658-413d995aa19d"
            }
          ]
        }
      ]
    },
    {
      "name": "Dynamicwrapperurl",
      "item": [
        {
          "id": "58d7c1e2-86a4-4c8a-8e4d-1f90589c8ac3",
          "name": "ClientsDynamicwrapperurlPost",
          "request": {
            "url": "http://example.com/clients/dynamicwrapperurl",
            "method": "POST",
            "header": [
              {
                "key": "accesskey",
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
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "dynamicURL",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Set wrapper URL. This is the global url."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "da70e78c-e186-4bcd-8351-c86400008db2"
            }
          ]
        }
      ]
    },
    {
      "name": "Featured",
      "item": [
        {
          "id": "8341887b-366a-4c2d-9e3f-2ae40a306d0b",
          "name": "ClientsFeaturedGet",
          "request": {
            "url": "http://example.com/clients/featured",
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
            "description": "Returns a basic set of information for all of the client's featured (active) properties"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bf627169-acc8-4401-9c22-e028a941daeb"
            }
          ]
        }
      ]
    },
    {
      "name": "List",
      "item": [
        {
          "id": "cc4bc384-617b-4a62-b2b1-9e9be595fd8b",
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
              "id": "84ca6618-fe6e-418e-8db4-d2d293f70fb2"
            }
          ]
        },
        {
          "id": "90ed92da-cb79-4178-a4e9-696459f2065b",
          "name": "ClientsListmethodsGet",
          "request": {
            "url": "http://example.com/clients/listmethods",
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
            "description": "A simple method for listing all available methods in the current API component."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b8dd52a4-4393-4010-83c2-ea7d57af7cc9"
            }
          ]
        }
      ]
    },
    {
      "name": "Listcomponents",
      "item": [
        {
          "id": "6cf02080-5806-4377-900b-357b97ec09a0",
          "name": "ClientsListcomponentsGet",
          "request": {
            "url": "http://example.com/clients/listcomponents",
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
            "description": "This is a simple, access anywhere, method for getting a list of all API components available."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e3650881-7dc8-4f55-bdf1-1d6cb833d1d0"
            }
          ]
        }
      ]
    },
    {
      "name": "Listing",
      "item": [
        {
          "id": "087186c3-adfb-4101-93c9-4de5ff2d6da9",
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
              "id": "80077cac-e822-4818-8a9b-ebf5627e379b"
            }
          ]
        }
      ]
    },
    {
      "name": "Offices",
      "item": [
        {
          "id": "2346d10c-ff08-4b1d-b163-a952637515a4",
          "name": "ClientsOfficesGet",
          "request": {
            "url": "http://example.com/clients/offices",
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
            "description": "View all offices on a mutli-user account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0aa38ae0-ef33-4e3a-bcd2-c49ff7d1303e"
            }
          ]
        }
      ]
    },
    {
      "name": "Alcodes",
      "item": [
        {
          "id": "13f911d8-d11c-4dac-8a5d-6309c1b099ee",
          "name": "ClientsPostalcodesGet",
          "request": {
            "url": "http://example.com/clients/postalcodes",
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
            "description": "Returns the postalcodes available in each of a client's postalcode lists."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9acf8f08-3f80-42a2-9c43-561c5aab2f08"
            }
          ]
        }
      ]
    },
    {
      "name": "Alcodeslistname",
      "item": [
        {
          "id": "0de5e76f-5d1d-4aa0-a88a-effe84250c14",
          "name": "ClientsPostalcodeslistnameGet",
          "request": {
            "url": "http://example.com/clients/postalcodeslistname",
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
            "description": "Returns the IDs and names for each of a client's postalcode lists including MLS postalcode lists."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "de8103af-806d-471f-8d0e-ceed4f7f85fa"
            }
          ]
        }
      ]
    },
    {
      "name": "Saved",
      "item": [
        {
          "id": "4412eda6-24e3-445a-a565-3cfd433c05c3",
          "name": "ClientsSavedlinksGet",
          "request": {
            "url": "http://example.com/clients/savedlinks",
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
            "description": "Getclient saved links"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a8f66f67-f46b-4ec1-bd60-cd9e36fd670c"
            }
          ]
        },
        {
          "id": "4615865a-7fa5-4aac-ae97-8597c2004cb6",
          "name": "ClientsSavedlinksPut",
          "request": {
            "url": "http://example.com/clients/savedlinks",
            "method": "PUT",
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
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "linkName",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "linkTitle",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "pageTitle",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "queryString[hp]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "queryString[idxID]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Create a new client saved link"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4862a1d1-f1b0-4d4b-8e42-926c985e3368"
            }
          ]
        },
        {
          "id": "5aca968e-510c-4499-bae3-195a29236f35",
          "name": "ClientsSavedlinksBySavedLinkIdPost",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "clients/savedlinks/:savedLinkId"
              ],
              "variable": [
                {
                  "id": "savedLinkId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
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
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "linkName",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "linkTitle",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "pageTitle",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "queryString[hp]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "queryString[idxID]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Update a client saved link"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "15a650a3-1dbd-4b14-9420-28daa16d6016"
            }
          ]
        },
        {
          "id": "86e5f23f-b526-43c5-8dab-f4854a1985c1",
          "name": "ClientsSavedlinksBySavedLinkIdDelete",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "clients/savedlinks/:savedLinkId"
              ],
              "variable": [
                {
                  "id": "savedLinkId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
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
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "linkName",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "linkTitle",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "pageTitle",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "queryString[hp]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "queryString[idxID]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Delete a client saved link"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "330841c2-f744-468d-94af-b2e2d3ff074a"
            }
          ]
        }
      ]
    },
    {
      "name": "Properties",
      "item": [
        {
          "id": "d53cd263-418e-4805-899a-06b759b9863c",
          "name": "ClientsPropertiesBySavedLinkIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "clients/properties/:savedLinkId"
              ],
              "variable": [
                {
                  "id": "savedLinkId",
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
            "description": "Get client saved links results"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "580d6eb7-430c-4fbd-b4e5-d0608f4dae20"
            }
          ]
        }
      ]
    },
    {
      "name": "Search",
      "item": [
        {
   