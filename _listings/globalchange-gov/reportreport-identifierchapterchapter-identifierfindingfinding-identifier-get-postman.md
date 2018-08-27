{
  "info": {
    "name": "Global Change Information System API Get a representation of a finding in a chapter.",
    "_postman_id": "bed10ba8-0149-439a-93b6-37152edfef41",
    "description": "Get JSON which represents the structure of a finding in a chapter.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Activities",
      "item": [
        {
          "id": "0ddc7a56-f699-489e-b429-8ee96a4f2dae",
          "name": "list-the-activities-20-per-page",
          "request": {
            "url": "http://data.globalchange.gov/activity?all=%7B%7D&page=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the activities, 20 per page."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5dc5be72-974a-45f0-a582-3bd29b3dd32d"
            }
          ]
        }
      ]
    },
    {
      "name": "Representation",
      "item": [
        {
          "id": "c758d569-f320-406d-8d75-951643c1bf7d",
          "name": "get-json-which-represents-the-structure-of-an-activity",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "activity/:activity_identifier"
              ],
              "variable": [
                {
                  "id": "activity_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of an activity."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1238dae3-4b54-4123-b613-37a9b3ee1857"
            }
          ]
        },
        {
          "id": "ed287e08-a97c-40cb-b2b8-79e725fd7d81",
          "name": "get-json-which-represents-the-structure-of-an-array",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "array/:array_identifier"
              ],
              "query": [
                {
                  "key": "with_gcmd",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "with_regions",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "array_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of an array."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5e987665-9958-4189-8e6f-6ff9e1a5c1a9"
            }
          ]
        },
        {
          "id": "92e9ec0f-5bc8-42c8-853a-bccdd165bde8",
          "name": "get-json-which-represents-the-structure-of-an-article",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "article/:article_identifier"
              ],
              "query": [
                {
                  "key": "with_gcmd",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "with_regions",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "article_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of an article."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0cd3cc69-8728-4777-ba3d-1526a56cfc18"
            }
          ]
        },
        {
          "id": "b56136a5-7803-4e54-8264-e4bbe37c01a8",
          "name": "get-json-which-represents-the-structure-of-a-book",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "book/:book_identifier"
              ],
              "query": [
                {
                  "key": "with_gcmd",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "with_regions",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "book_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of a book."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "46b33bfc-d0e0-4693-b507-979ef6fa98ea"
            }
          ]
        },
        {
          "id": "d1dc2f75-3e05-4833-8fdb-a401dec14e0a",
          "name": "get-json-which-represents-the-structure-of-a-dataset",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "dataset/:dataset_identifier"
              ],
              "variable": [
                {
                  "id": "dataset_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of a dataset."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a7c53bc1-08a2-4102-82ad-6f1a581a499d"
            }
          ]
        },
        {
          "id": "fefb067a-fa1d-40d2-b37b-8f4b75f138ac",
          "name": "get-json-which-represents-the-structure-of-a-file",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "file/:file_identifier"
              ],
              "variable": [
                {
                  "id": "file_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of a file."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4951b8ca-d0e3-4560-bce9-3851361d96c8"
            }
          ]
        },
        {
          "id": "7b56bda1-2b65-4511-a97e-78321f81faed",
          "name": "get-json-which-represents-the-structure-of-a-gcmd-keyword",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "gcmd_keyword/:gcmd_keyword_identifier"
              ],
              "variable": [
                {
                  "id": "gcmd_keyword_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of a GCMD keyword."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "31eb3b47-28f9-4e4a-90a7-cefe6dd9a79b"
            }
          ]
        },
        {
          "id": "8c482243-92e3-474c-9a2a-df9679c529a9",
          "name": "get-json-which-represents-the-structure-of-a-generic-publication",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "generic/:generic_identifier"
              ],
              "variable": [
                {
                  "id": "generic_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of a generic publication."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c466847e-f39f-42b4-ad3a-c63063b31e6d"
            }
          ]
        },
        {
          "id": "8b29fcfc-a012-4deb-91b5-63c64c0d7680",
          "name": "get-json-which-represents-the-structure-of-an-image",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "image/:image_identifier"
              ],
              "query": [
                {
                  "key": "with_gcmd",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "with_regions",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "image_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of an image."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "30bab731-dec0-4036-8b5a-15bcaefec0ac"
            }
          ]
        },
        {
          "id": "908cc607-b280-49b4-8c84-382153a45e7d",
          "name": "get-json-which-represents-the-structure-of-an-instrument",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "instrument/:instrument_identifier"
              ],
              "variable": [
                {
                  "id": "instrument_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of an instrument."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f9d39406-2e76-4a69-ae9b-4af2cc33d3d0"
            }
          ]
        },
        {
          "id": "59de2af4-fc42-4329-9caf-c8f8fe2065e7",
          "name": "get-json-which-represents-the-structure-of-a-journal",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "journal/:journal_identifier"
              ],
              "variable": [
                {
                  "id": "journal_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of a journal."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7a90a35b-95e8-480f-8f18-3e8a39f24fe5"
            }
          ]
        },
        {
          "id": "1287325d-0d58-44b4-ad75-8c5935c85dd7",
          "name": "get-json-which-represents-the-structure-of-a-lexicon",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "lexicon/:lexicon_identifier"
              ],
              "variable": [
                {
                  "id": "lexicon_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of a lexicon."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c7beb5bf-5bc8-4d62-956c-4fb03c16963e"
            }
          ]
        },
        {
          "id": "e0e4add4-894c-4676-95cc-e3473f8ed066",
          "name": "get-json-which-represents-the-structure-of-a-model",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "model/:model_identifier"
              ],
              "variable": [
                {
                  "id": "model_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of a model."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5ca53538-9a0a-4e77-8f5d-cc5d581fa72b"
            }
          ]
        },
        {
          "id": "0db9707a-91b8-45fa-ad35-1f8be05017e5",
          "name": "get-json-which-represents-the-structure-of-a-model-run",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "model_run/:model_identifier/:scenario_identifier/:range_start/:range_end/:spatial_resolution/:time_resolution/:sequence"
              ],
              "variable": [
                {
                  "id": "model_identifier",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "range_end",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "range_start",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "scenario_identifier",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "sequence",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "spatial_resolution",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "time_resolution",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of a model run."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "761bc5c5-45e0-4dfa-a972-d5c822448c75"
            }
          ]
        },
        {
          "id": "68a95e5a-e2ce-472f-b6c2-3a3ad8201001",
          "name": "get-json-which-represents-the-structure-of-a-model-run",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "model_run/:model_run_identifier"
              ],
              "variable": [
                {
                  "id": "model_run_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of a model run."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "07e6fb3c-d5b1-4963-ae86-82b2b36ca495"
            }
          ]
        },
        {
          "id": "403903c2-950f-4991-9845-1948b604b7cd",
          "name": "get-json-which-represents-the-structure-of-an-organization",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "organization/:organization_identifier"
              ],
              "variable": [
                {
                  "id": "organization_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of an organization."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e5244b0b-6527-4b9d-ba3e-418d84c5f1de"
            }
          ]
        },
        {
          "id": "24149d19-8d85-4ac8-982c-95c60b5e1c66",
          "name": "get-json-which-represents-the-structure-of-a-person",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "person/:person_identifier"
              ],
              "variable": [
                {
                  "id": "person_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of a person."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "675b28d3-0eec-43b4-9852-55534361c346"
            }
          ]
        },
        {
          "id": "e6b5cc42-af65-4dd2-9272-c877d79161ef",
          "name": "get-json-which-represents-the-structure-of-a-platform",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "platform/:platform_identifier"
              ],
              "variable": [
                {
                  "id": "platform_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of a platform."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e8c5ece9-025f-485c-ba75-71950c9c1f25"
            }
          ]
        },
        {
          "id": "54f86f40-2186-4bd7-8beb-d2364d8f5358",
          "name": "get-json-which-represents-the-structure-of-an-instrument-on-a-platform",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "platform/:platform_identifier/instrument/:instrument_identifier"
              ],
              "variable": [
                {
                  "id": "instrument_identifier",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "platform_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of an instrument on a platform."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0e2af810-9269-4a5f-8af9-70affb82c9ae"
            }
          ]
        },
        {
          "id": "7a3be2f8-1ea8-4743-b4b9-5b12d9ad58e0",
          "name": "get-json-which-represents-the-structure-of-a-project",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "project/:project_identifier"
              ],
              "variable": [
                {
                  "id": "project_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of a project."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dc9b126a-5f54-45ac-8266-b209bae210e1"
            }
          ]
        },
        {
          "id": "ae60dc5b-b13b-48ec-9e59-2c819b266b1b",
          "name": "get-json-which-represents-the-structure-of-a-reference",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "reference/:reference_identifier"
              ],
              "variable": [
                {
                  "id": "reference_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of a reference."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3f1319b6-085f-4fbf-a1f2-8a6fa9c9c37e"
            }
          ]
        },
        {
          "id": "32061ecc-ae71-49f5-9315-44836c464904",
          "name": "get-json-which-represents-the-structure-of-a-region",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "region/:region_identifier"
              ],
              "variable": [
                {
                  "id": "region_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of a region."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a6da8994-f1be-4e97-993e-a8ce096843f8"
            }
          ]
        },
        {
          "id": "de99e411-6efc-41c0-aabc-d8a8a0e1c9e1",
          "name": "get-json-which-represents-the-structure-of-a-report",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "report/:report_identifier"
              ],
              "query": [
                {
                  "key": "with_gcmd",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "with_regions",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "report_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of a report."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "69006434-3147-4912-9ead-fbbba7f1ce42"
            }
          ]
        },
        {
          "id": "3ddeb259-d9d1-4fc9-86d1-bb261cf02288",
          "name": "get-json-which-represents-the-structure-of-a-chapter",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "report/:report_identifier/chapter/:chapter_identifier"
              ],
              "query": [
                {
                  "key": "ids",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "with_gcmd",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "with_regions",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "chapter_identifier",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "report_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of a chapter."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7c104f3d-b523-4a77-819f-470ac77f4bfe"
            }
          ]
        },
        {
          "id": "92b3d5f8-3877-4ee4-b226-a2ece3e8c409",
          "name": "get-json-which-represents-the-structure-of-a-figure-in-a-chapter",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "report/:report_identifier/chapter/:chapter_identifier/figure/:figure_identifier"
              ],
              "query": [
                {
                  "key": "ids",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "with_gcmd",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "with_regions",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "chapter_identifier",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "figure_identifier",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "report_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of a figure in a chapter."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d3535d41-2b93-4c8a-941d-9860601db99c"
            }
          ]
        },
        {
          "id": "98eb1029-57cb-4f4a-9673-db7364c4bb9d",
          "name": "get-json-which-represents-the-structure-of-a-finding-in-a-chapter",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "report/:report_identifier/chapter/:chapter_identifier/finding/:finding_identifier"
              ],
              "query": [
                {
                  "key": "with_gcmd",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "with_regions",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "chapter_identifier",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "finding_identifier",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "report_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of a finding in a chapter."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0f2d84d1-8914-40bc-9f61-aa953ac46b35"
            }
          ]
        }
      ]
    },
    {
      "name": "Arrays",
      "item": [
        {
          "id": "97f7ba31-c2d2-466f-9565-1c0a0683f8ac",
          "name": "list-the-arrays-20-per-page",
          "request": {
            "url": "http://data.globalchange.gov/array?all=%7B%7D&page=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the arrays, 20 per page."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "569e4a45-97cc-4ce1-9da2-1c710be6766b"
            }
          ]
        },
        {
          "id": "86f717d5-9bb8-4385-9cc8-6e63f08f92bd",
          "name": "list-the-arrays-associated-with-a-report-20-per-page",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "report/:report_identifier/array"
              ],
              "query": [
                {
                  "key": "all",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "page",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "report_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the arrays associated with a report, 20 per page."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "796dabae-9c75-4b77-8ae5-039cd4746018"
            }
          ]
        }
      ]
    },
    {
      "name": "Articles",
      "item": [
        {
          "id": "57b85709-3cc7-45cf-84ad-debf8c2516d9",
          "name": "list-the-articles-20-per-page",
          "request": {
            "url": "http://data.globalchange.gov/article?all=%7B%7D&page=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the articles, 20 per page."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "855b2190-c2a5-4ec0-9d19-313ec65dcee7"
            }
          ]
        }
      ]
    },
    {
      "name": "Books",
      "item": [
        {
          "id": "937c7452-a1d2-4c32-8963-10f77e248fde",
          "name": "list-the-books-20-per-page",
          "request": {
            "url": "http://data.globalchange.gov/book?all=%7B%7D&page=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the books, 20 per page."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3f312359-1c82-4be6-b143-77f0583738c8"
            }
          ]
        },
        {
          "id": "600fe435-a543-46ba-8bf5-b0268cb14bcd",
          "name": "list-the-books-associated-with-a-report-20-per-page",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "report/:report_identifier/book"
              ],
              "query": [
                {
                  "key": "all",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "page",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "report_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the books associated with a report, 20 per page."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e578aae8-3185-4bcf-8f6c-c556567c1cce"
            }
          ]
        }
      ]
    },
    {
      "name": "Redirect",
      "item": [
        {
          "id": "b8f24b12-ec21-4f77-9601-3a0b0c01c156",
          "name": "given-a-numeric-id-redirect-to-the-full-uri-of-a-contributor",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "contributor/:contributor_identifier"
              ],
              "variable": [
                {
                  "id": "contributor_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Given a numeric ID, redirect to the full URI of a contributor."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b44c994b-dcfd-4807-8080-bacbf5bdea36"
            }
          ]
        },
        {
          "id": "21ff6d44-50c8-4a61-8ce6-710aa32c5d81",
          "name": "given-a-name-case-sensitive-concatenated-by-dashes-redirect-if-there-is-a-single-match--the-first-an",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "person/:name"
              ],
              "variable": [
                {
                  "id": "name",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Given a name (case sensitive, concatenated by dashes), redirect if there is a single match.  The first and last names can be in either order."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ec2d15c4-a04a-4a54-8327-7eba0cee749a"
            }
          ]
        },
        {
          "id": "85490117-27db-44cf-a311-6b8fcc26cc18",
          "name": "given-an-orcid-if-there-is-a-match-redirect-to-the-persons-uri",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "person/:orcid"
              ],
              "variable": [
                {
                  "id": "orcid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Given an ORCID, if there is a match, redirect to the persons URI."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7bdca46c-60b4-4617-a209-132eaf8a774a"
            }
          ]
        },
        {
          "id": "05e3b54b-2250-4447-a18b-3990bae29418",
          "name": "given-a-numeric-id-redirect-to-the-full-uri-of-a-publication",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "publication/:publication_identifier"
              ],
              "variable": [
                {
                  "id": "publication_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Given a numeric ID, redirect to the full URI of a publication."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5c42470f-b1af-42da-ba7c-523009685375"
            }
          ]
        }
      ]
    },
    {
      "name": "Datasets",
      "item": [
        {
          "id": "9f701db7-5e7f-48d8-80eb-e9bb4434891c",
          "name": "list-the-datasets-20-per-page",
          "request": {
            "url": "http://data.globalchange.gov/dataset?all=%7B%7D&page=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the datasets, 20 per page."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "77e23bd9-94d3-404b-a3fb-266a2b5304d5"
            }
          ]
        }
      ]
    },
    {
      "name": "Look",
      "item": [
        {
          "id": "576458d3-7b40-45b4-99e2-65fbb57ff848",
          "name": "given-a-doi-return-a-redirect-to-the-gcis-dataset",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "dataset/lookup/:doi"
              ],
              "variable": [
                {
                  "id": "doi",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Given a DOI, return a redirect to the GCIS dataset."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ac379361-9a82-4edd-8055-45b3964db345"
            }
          ]
        }
      ]
    },
    {
      "name": "Folder",
      "item": [
        {
          "id": "0304cd5c-55d6-4d08-91b7-6a1128bf3d72",
          "name": "list-all-the-figures-in-gcis",
          "request": {
            "url": "http://data.globalchange.gov/figure?all=%7B%7D&page=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List all the figures in GCIS."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "68aeb9b1-68af-4ebc-9f6b-b5fb431209a6"
            }
          ]
        }
      ]
    },
    {
      "name": "GCMD",
      "item": [
        {
          "id": "9575004f-eef2-42f9-9ffa-db172ba25085",
          "name": "list-the-gcmd-keywords-in-the-gcis-20-per-page",
          "request": {
            "url": "http://data.globalchange.gov/gcmd_keyword?page=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the GCMD keywords in the GCIS, 20 per page."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1c5b274c-ce33-4f67-a0a8-54633976e4ba"
            }
          ]
        }
      ]
    },
    {
      "name": "Generic",
      "item": [
        {
          "id": "7895385c-7323-47e1-93e6-b6412d849c4b",
          "name": "list-the-generic-publications-20-per-page",
          "request": {
            "url": "http://data.globalchange.gov/generic?all=%7B%7D&page=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the generic publications, 20 per page."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7ee9b7c3-73aa-4604-94e7-d57374d3861b"
            }
          ]
        }
      ]
    },
    {
      "name": "Images",
      "item": [
        {
          "id": "3cfc2df4-c160-45ab-9e30-5e1fd7036e6f",
          "name": "list-the-images-20-per-page",
          "request": {
            "url": "http://data.globalchange.gov/image?all=%7B%7D&page=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the images, 20 per page."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e69903bc-ad5f-47e7-8831-f08b6deb4db4"
            }
          ]
        }
      ]
    },
    {
      "name": "Instruments",
      "item": [
        {
          "id": "0d2e2dab-3b0f-4ece-92e3-c0199f41f6fd",
          "name": "list-the-instruments-20-per-page",
          "request": {
            "url": "http://data.globalchange.gov/instrument?all=%7B%7D&page=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the instruments, 20 per page."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0b83b715-2dd4-4bd6-a445-a6101b508348"
            }
          ]
        },
        {
          "id": "9857ef1a-850b-4cb3-abb3-65b864648b06",
          "name": "list-the-instruments-on-a-platform-20-per-page",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "platform/:platform_identifier/instrument"
              ],
              "query": [
                {
                  "key": "all",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "page",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "platform_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the instruments on a platform, 20 per page."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dd82c905-a22e-4c55-b5bb-bc4a653d5850"
            }
          ]
        }
      ]
    },
    {
      "name": "Journals",
      "item": [
        {
          "id": "6932f8e5-85d1-4839-8d49-313b963d000d",
          "name": "list-the-journals-20-per-page",
          "request": {
            "url": "http://data.globalchange.gov/journal?all=%7B%7D&page=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the journals, 20 per page."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f14c9e07-ab62-4954-a266-a478aff61318"
            }
          ]
        }
      ]
    },
    {
      "name": "Lexicons",
      "item": [
        {
          "id": "17b67d64-5778-46e2-bd30-db7a0dc1d0f5",
          "name": "list-the-lexicons-20-per-page",
          "request": {
            "url": "http://data.globalchange.gov/lexicon?all=%7B%7D&page=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the lexicons, 20 per page."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0ecb939c-89d3-44b1-9f72-276cac02a413"
            }
          ]
        }
      ]
    },
    {
      "name": "Lookup",
      "item": [
        {
          "id": "96ebcc38-a9b3-4525-8336-a611f9ebd0c2",
          "name": "given-a-lexicon-term-and-context-return-a-303-redirect-to-a-gcid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "lexicon/:lexicon_identifier/find/:context/:term"
              ],
              "variable": [
                {
                  "id": "context",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "lexicon_identifier",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "term",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Given a lexicon, term, and context, return a 303 redirect to a GCID"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3b1c23f9-b927-425b-8bf0-84f7d4130b41"
            }
          ]
        },
        {
          "id": "ea40989a-d1ec-40f1-b729-631668aeee7c",
          "name": "given-a-lexicon-term-and-context-return-a-303-redirect-to-a-gcid1",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "lexicon/:lexicon_identifier/:context/:term"
              ],
              "variable": [
                {
                  "id": "context",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "lexicon_identifier",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "term",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Given a lexicon, term, and context, return a 303 redirect to a GCID"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "40260a20-c759-4444-aeb0-22c7cafc691a"
            }
          ]
        }
      ]
    },
    {
      "name": "Terms",
      "item": [
        {
          "id": "e5f807ec-03d4-4c13-990d-2f7b41ccada4",
          "name": "list-the-terms-within-a-context-of-a-lexicon",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "lexicon/:lexicon_identifier/list/:context"
              ],
              "variable": [
                {
                  "id": "context",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "lexicon_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the terms within a context of a lexicon"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3520122b-d517-408a-83a8-d0e96fa8331e"
            }
          ]
        }
      ]
    },
    {
      "name": "Overall",
      "item": [
        {
          "id": "d1501a4d-6e05-44f2-8d00-795c7eb63254",
          "name": "get-overall-metrics-about-gcis-data",
          "request": {
            "url": "http://data.globalchange.gov/metrics",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get overall metrics about GCIS data"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "655de0bb-b52a-49ec-983f-4a0eb60f807f"
            }
          ]
        }
      ]
    },
    {
      "name": "Models",
      "item": [
        {
          "id": "803955bd-0379-472e-b13b-201329cb040c",
          "name": "list-the-models-20-per-page",
          "request": {
            "url": "http://data.globalchange.gov/model?all=%7B%7D&page=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the models, 20 per page."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c87b48c0-b9cf-4634-991e-8a8733d1ffbc"
            }
          ]
        }
      ]
    },
    {
      "name": "Model",
      "item": [
        {
          "id": "b711b578-98fb-44e9-be33-a4d34c4a2ea1",
          "name": "list-the-model-runs-for-a-particular-model-20-per-page",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "model/:model_identifier/run"
              ],
              "query": [
                {
                  "key": "all",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "page",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "model_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the model runs for a particular model, 20 per page."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0a1a8fd8-c573-4917-a356-c1a38325a23c"
            }
          ]
        },
        {
          "id": "e8aa8798-8808-4604-8163-a304740e4d51",
          "name": "list-the-model-runs-20-per-page",
          "request": {
            "url": "http://data.globalchange.gov/model_run?all=%7B%7D&page=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the model runs, 20 per page."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3560fe19-4fe9-4235-bc58-fd978250b5a1"
            }
          ]
        }
      ]
    },
    {
      "name": "Organizations",
      "item": [
        {
          "id": "9a597704-b96b-433a-9c1a-e54fa0384e92",
          "name": "list-the-organizations-20-per-page",
          "request": {
            "url": "http://data.globalchange.gov/organization?all=%7B%7D&page=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the organizations, 20 per page."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "feaff9c6-f0ab-4125-9ddb-9a74033d5966"
            }
          ]
        }
      ]
    },
    {
      "name": "Show",
      "item": [
        {
          "id": "4e5a3032-08d3-42e6-9a93-9e9cc7107378",
          "name": "given-a-resource-dataset-report-etc-and-a-role-editor-etc-and-an-identifier-for-an-organization-show",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "organization/:organization_identifier/contributions/:role_type_identifier/:resource"
              ],
              "variable": [
                {
                  "id": "organization_identifier",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "resource",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "role_type_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Given a resource (dataset, report, etc.) and a role (editor, etc), and an identifier for an organization, show the resources to which the organization has contributed in that role."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dde51448-79ac-4de8-826f-f7718a4d2729"
            }
          ]
        },
        {
          "id": "a35590f4-4323-4057-9f20-cd0636a051b7",
          "name": "given-a-resource-dataset-report-etc-and-a-role-editor-etc-and-an-identifier-for-a-person-show-the-re",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "person/:person_identifier/contributions/:role_type_identifier/:resource"
              ],
              "variable": [
                {
                  "id": "person_identifier",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "resource",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "role_type_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Given a resource (dataset, report, etc.) and a role (editor, etc), and an identifier for a person, show the resources to which the person has contributed in that role."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ea22ad1c-d0c3-4952-bb43-cfd065334c5b"
            }
          ]
        }
      ]
    },
    {
      "name": "People",
      "item": [
        {
          "id": "fa8379cc-2d93-4ff2-b286-f91723078662",
          "name": "list-the-people-20-per-page",
          "request": {
            "url": "http://data.globalchange.gov/person?all=%7B%7D&page=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the people, 20 per page."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "afc0acf1-e8d7-471e-b6d4-914815106efc"
            }
          ]
        }
      ]
    },
    {
      "name": "Platforms",
      "item": [
        {
          "id": "2ce6563b-b184-4928-b3c1-92867cacc5f5",
          "name": "list-the-platforms-20-per-page",
          "request": {
            "url": "http://data.globalchange.gov/platform?all=%7B%7D&page=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the platforms, 20 per page."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "29bd86ab-e962-4b0f-be4d-46be7bbd9c35"
            }
          ]
        }
      ]
    },
    {
      "name": "Projects",
      "item": [
        {
          "id": "f5f0c524-5953-4ef1-ad9a-b4d21098edbf",
          "name": "list-the-projects-20-per-page",
          "request": {
            "url": "http://data.globalchange.gov/project?all=%7B%7D&page=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the projects, 20 per page."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c617f7ed-1283-4989-8ad0-5dc968bd6b4f"
            }
          ]
        }
      ]
    },
    {
      "name": "References",
      "item": [
        {
          "id": "2798d1c9-c141-4ae8-af21-0771347d0d47",
          "name": "list-the-references-20-per-page",
          "request": {
            "url": "http://data.globalchange.gov/reference?page=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the references, 20 per page."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8904944d-67bd-4fa0-b2dc-e0ea3c9ec30d"
            }
          ]
        }
      ]
    },
    {
      "name": "Regions",
      "item": [
        {
          "id": "87df9a7c-9076-46d5-aab8-8d6831437fa8",
          "name": "list-the-regions-20-per-page",
          "request": {
            "url": "http://data.globalchange.gov/region?all=%7B%7D&page=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the regions, 20 per page."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "434c48c6-ec41-4267-9101-92f18f87e02c"
            }
          ]
        }
      ]
    },
    {
      "name": "Reports",
      "item": [
        {
          "id": "abca6beb-0cf5-45e1-b1ab-f94d28ca082f",
          "name": "list-the-reports-20-per-page",
          "request": {
            "url": "http://data.globalchange.gov/report?all=%7B%7D&page=%7B%7D&report_type=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the reports, 20 per page."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a1227a71-190c-406b-97f3-dda9032202b7"
            }
          ]
        }
    