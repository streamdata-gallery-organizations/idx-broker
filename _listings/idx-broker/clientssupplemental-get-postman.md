{
  "info": {
    "name": "IDX Broker Get Supplemental",
    "_postman_id": "8f989f33-99b4-41e5-9c5b-0b36cc8207b9",
    "description": "Get supplemental listings.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Approved",
      "item": [
        {
          "id": "50619078-5549-48f3-a17a-637f5e857195",
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
              "id": "da66e905-fb5b-4ded-8089-feb2f08f9622"
            }
          ]
        }
      ]
    },
    {
      "name": "Mls",
      "item": [
        {
          "id": "b6b28ceb-ec7b-454c-83d9-689979839247",
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
              "id": "b2d05340-19a6-41e2-9996-23339642f4fd"
            }
          ]
        },
        {
          "id": "345e1bec-6eb4-46e0-acd1-f50cc7873053",
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
              "id": "45556ad8-f114-4efb-969b-a9c487446058"
            }
          ]
        },
        {
          "id": "1fd9117a-6586-40e8-833c-c0a2d37540aa",
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
              "id": "6d338856-2dd2-4412-8970-6ab84473d7f4"
            }
          ]
        },
        {
          "id": "010ff3fa-5ba8-4c91-aaa2-1c786aad77b3",
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
              "id": "85d68367-993e-4904-b05f-cf76a43133d3"
            }
          ]
        },
        {
          "id": "17bf5265-7fa7-4092-9ea5-732dbc3f18d2",
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
              "id": "400970bc-0655-4f1c-bfa6-437d5757180f"
            }
          ]
        },
        {
          "id": "1eefeee3-d671-4a48-8f51-35ec80b0189b",
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
              "id": "eef8ac1f-6089-4f20-9d3a-1355622fca6b"
            }
          ]
        },
        {
          "id": "ad91888b-1660-4ddb-9e17-e3edfc75e6ad",
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
              "id": "5ea8186d-1807-49bb-ad96-bc23591b7a21"
            }
          ]
        },
        {
          "id": "71b216eb-2858-410c-8566-635d47837fc4",
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
              "id": "dfbdae9a-b555-490d-970b-12fa19d7dbc6"
            }
          ]
        },
        {
          "id": "a7ca2db8-094b-4582-99df-8ae94465b510",
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
              "id": "78a949f4-bbc7-4038-be88-3d86ba245351"
            }
          ]
        },
        {
          "id": "c86c7e33-ed38-4360-b75b-5fdbf7bc1f63",
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
              "id": "6f5412be-43be-4364-bc4f-69f31d4501f8"
            }
          ]
        },
        {
          "id": "8b4c14f3-c361-4539-b8cb-2f286d398036",
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
              "id": "941891fc-0d39-45da-86b6-2fb299a718ff"
            }
          ]
        }
      ]
    },
    {
      "name": "Agents",
      "item": [
        {
          "id": "7bfcb1ab-b303-4dda-9454-db5a0131a9de",
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
              "id": "45f8e928-f20f-4563-a776-8cdd7ad0c321"
            }
          ]
        }
      ]
    },
    {
      "name": "Apiversion",
      "item": [
        {
          "id": "5482e342-0166-4c65-98b6-59c1cea406d9",
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
              "id": "cda871b0-fb37-4a8e-aee5-3e8f535e871d"
            }
          ]
        }
      ]
    },
    {
      "name": "Cities",
      "item": [
        {
          "id": "8cab8cbb-dc6d-49dd-82ee-fb64eac6726e",
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
              "id": "9e3ed97d-9201-49d0-a28d-3a6da37934de"
            }
          ]
        },
        {
          "id": "d20c7694-ebf0-482b-85e4-463b91f5a625",
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
              "id": "6c54b5a1-b0c7-4168-a83f-acf3dcb96f8a"
            }
          ]
        }
      ]
    },
    {
      "name": "Counties",
      "item": [
        {
          "id": "a54365a4-b84e-48d1-af36-fb2536f441aa",
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
              "id": "ae83a9b0-b566-488e-b2a6-3c253361e19e"
            }
          ]
        }
      ]
    },
    {
      "name": "Countieslistname",
      "item": [
        {
          "id": "7c992a80-eeae-4630-b006-f14329185445",
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
              "id": "c340c247-d8d3-47aa-b866-156f6a224f92"
            }
          ]
        }
      ]
    },
    {
      "name": "Dynamicwrapperurl",
      "item": [
        {
          "id": "d55c91b6-d476-4ce1-8965-931835067763",
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
              "id": "07523174-11f0-45c3-ac09-ec26c962cafb"
            }
          ]
        }
      ]
    },
    {
      "name": "Featured",
      "item": [
        {
          "id": "80e0612d-4baf-4222-a582-3072344c6cc9",
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
              "id": "c0ed35b7-fc4a-4c5b-a49f-da48ca810b4d"
            }
          ]
        }
      ]
    },
    {
      "name": "List",
      "item": [
        {
          "id": "636dc9be-dd83-4e95-8039-a66c9f49e437",
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
              "id": "051cd84e-60e6-44f4-8836-fbf7857caa8c"
            }
          ]
        },
        {
          "id": "71a03bba-ae56-4c1e-85da-7c3f5463ec6a",
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
              "id": "e863581f-6297-4b27-9efe-805d6f92b0b7"
            }
          ]
        }
      ]
    },
    {
      "name": "Listcomponents",
      "item": [
        {
          "id": "b7fa8080-73f2-4cf5-9b72-12cea3f64899",
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
              "id": "64eff3ba-b18c-4c9b-b981-318d7b7a288f"
            }
          ]
        }
      ]
    },
    {
      "name": "Listing",
      "item": [
        {
          "id": "b687a8b8-39ec-4b26-9747-c1f811e0b63e",
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
              "id": "0ed74bfc-3165-4b68-9b0f-4a6d5bf805de"
            }
          ]
        }
      ]
    },
    {
      "name": "Offices",
      "item": [
        {
          "id": "98d29324-9221-439f-83d5-9b5be434ac8b",
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
              "id": "36f97006-c2fe-4292-a6c8-f01af8cdbe51"
            }
          ]
        }
      ]
    },
    {
      "name": "Alcodes",
      "item": [
        {
          "id": "7342539b-5b71-4079-a018-007e986bbc1d",
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
              "id": "43d65b8a-5495-4fa4-ba07-f3fb0d7ef34f"
            }
          ]
        }
      ]
    },
    {
      "name": "Alcodeslistname",
      "item": [
        {
          "id": "6e06ea5b-f895-4c1b-98dd-e6a4c8e96052",
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
              "id": "ab02648d-d1fb-4a48-bd5f-a09d75ce0d4f"
            }
          ]
        }
      ]
    },
    {
      "name": "Saved",
      "item": [
        {
          "id": "94b45708-c068-4ebc-8085-04a64b318616",
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
              "id": "4d46bd10-f7ec-40dc-979f-6b686da9db3a"
            }
          ]
        },
        {
          "id": "62c78afe-0059-4eb7-9027-498eee883090",
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
              "id": "570932ea-5bbd-4b31-a1e8-3c109a884b72"
            }
          ]
        },
        {
          "id": "7234e287-afc7-4561-a7d2-72b5d659cfd0",
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
              "id": "33c6e756-8f42-4ef4-a63a-87185d575a4e"
            }
          ]
        },
        {
          "id": "5cc3704c-933c-4b94-92d0-9e967a2a4422",
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
              "id": "f45faa87-5548-4967-944b-444832948c69"
            }
          ]
        }
      ]
    },
    {
      "name": "Properties",
      "item": [
        {
          "id": "9561343a-4a09-4db5-9d54-143ec0ca9b63",
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
              "id": "407d5d45-f26b-4764-99ce-6a145d2e1349"
            }
          ]
        }
      ]
    },
    {
      "name": "Search",
      "item": [
        {
          "id": "5d30d571-d2dd-4221-bcdc-2551e33a3349",
          "name": "ClientsSearchqueryGet",
          "reque