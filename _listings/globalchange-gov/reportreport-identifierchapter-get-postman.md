{
  "info": {
    "name": "Global Change Information System API List chapters in a report",
    "_postman_id": "554aa656-7990-4763-95c5-75243719aadd",
    "description": "Get a list of chapters in a report.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Activities",
      "item": [
        {
          "id": "1585aae4-ab17-4263-95e8-d14d105fc000",
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
              "id": "6e54b433-4148-40f0-8b2c-a160754cd8d7"
            }
          ]
        }
      ]
    },
    {
      "name": "Representation",
      "item": [
        {
          "id": "f1c8e5d1-86e6-4cdd-b7cc-95486a1ab34d",
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
              "id": "5513f7ba-c525-4358-a2d2-91c767bca15b"
            }
          ]
        },
        {
          "id": "56b4c743-e90f-48bf-b483-71bd07360f59",
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
              "id": "88d197b0-9ca7-4973-a0a9-8e0879d9a35c"
            }
          ]
        },
        {
          "id": "81645dd0-42d5-49a5-8991-fe898d22c425",
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
              "id": "959bef53-4d22-4968-adde-98914fe4514d"
            }
          ]
        },
        {
          "id": "d6f9d0dc-2c57-41a8-9b05-815ad1f98560",
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
              "id": "e4bbc99e-2f00-4a31-9f1a-54013a2af34f"
            }
          ]
        },
        {
          "id": "4d8d62de-5e38-4061-a39f-97fc4449ceb6",
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
              "id": "b664ac6b-b2e9-439b-9fdf-bbdad4d595dd"
            }
          ]
        },
        {
          "id": "92cd1f6e-94d1-459d-9b9c-27fe2a32f4fb",
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
              "id": "f5cadb73-5331-4927-a9c7-a8112f301917"
            }
          ]
        },
        {
          "id": "ae871689-b28b-4cf2-9f69-e84bbfa04097",
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
              "id": "d094edb4-e04e-42dd-b045-8b9e50f89c43"
            }
          ]
        },
        {
          "id": "9de5cb90-70c0-4015-aedc-6f437fe21670",
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
              "id": "599f9932-920a-4049-b27a-300e2e0f8773"
            }
          ]
        },
        {
          "id": "be55aca9-a53f-4e05-83ea-6e5278032d26",
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
              "id": "358b4f8d-7169-481e-9529-20ecec055cce"
            }
          ]
        },
        {
          "id": "9a3555d9-adb9-4298-99d8-faad504421d7",
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
              "id": "3160ebb6-9214-4b99-9a92-1d8c6fdc9f9d"
            }
          ]
        },
        {
          "id": "4bc4f0de-4645-4ab4-96ba-daae865f6c28",
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
              "id": "7db36c78-be97-423e-a075-3e5b80e56a48"
            }
          ]
        },
        {
          "id": "45efdb3d-dac5-40f0-88ad-3c0f230a2519",
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
              "id": "b9485437-bbd3-44c1-9a32-44e83a2ee5ba"
            }
          ]
        },
        {
          "id": "033b6218-106d-4b1c-a179-411ba1b6a16b",
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
              "id": "33ce5df0-b04c-4959-b5c7-03187125c87a"
            }
          ]
        },
        {
          "id": "e3fe2904-aee9-47d8-a733-c456b4d98c4d",
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
              "id": "c894298d-a6cf-4cc5-96a4-1e45576c728c"
            }
          ]
        },
        {
          "id": "c21eaed1-ee54-495a-9c11-f8ab83a0843f",
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
              "id": "a1d319fb-9b0b-4312-9c68-20a6e7384cde"
            }
          ]
        },
        {
          "id": "41b344bc-0680-4e70-9578-f0d379503e86",
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
              "id": "8c3f60d0-0a80-4636-827a-aa7f576b9065"
            }
          ]
        },
        {
          "id": "e06f6ab3-6521-4c95-87d6-4d270675918a",
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
              "id": "13df7083-dee0-4474-b46f-abd295a23a6a"
            }
          ]
        },
        {
          "id": "afbf040f-7e9c-4557-8aee-0bc25405c729",
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
              "id": "9aa5760d-4967-4b1a-887b-aefe6f023e68"
            }
          ]
        },
        {
          "id": "60ed155c-e259-4f08-9ec5-bd533791a661",
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
              "id": "be0de037-6638-462b-a45c-6953aaa0e15a"
            }
          ]
        },
        {
          "id": "5c39ce96-7c8f-46ca-ba4b-439d34b4a67f",
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
              "id": "ecca6c24-0549-4558-b123-be9351358a52"
            }
          ]
        },
        {
          "id": "f5c1e8e7-b861-40a1-97d8-e12c3d4519b2",
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
              "id": "1f8f6646-e97d-46a1-8d55-6b594f48e820"
            }
          ]
        },
        {
          "id": "ae406445-cd8a-4e4a-9e43-0e721d2b25ac",
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
              "id": "caa7daaf-6774-41b2-b5e8-6dc212368e9b"
            }
          ]
        },
        {
          "id": "b5591a01-1e62-4048-853b-33a5ec4daa6a",
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
              "id": "ffad3641-753a-4b66-afcd-e036aaec171a"
            }
          ]
        }
      ]
    },
    {
      "name": "Arrays",
      "item": [
        {
          "id": "b8859ee3-2673-459d-a838-a6cc9a08d363",
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
              "id": "84f5f714-fc99-4c0d-b662-8de6d53095e4"
            }
          ]
        },
        {
          "id": "45e87dcb-62c0-4c89-8641-323bfcc4d080",
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
              "id": "e6fc310a-2102-4909-ab4b-0c7fac3e94a2"
            }
          ]
        }
      ]
    },
    {
      "name": "Articles",
      "item": [
        {
          "id": "436b1a92-231d-4b7c-9fd9-b6f21a4b9e69",
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
              "id": "1ab2bb6d-ff14-4c62-9d38-f7d6c892f7ed"
            }
          ]
        }
      ]
    },
    {
      "name": "Books",
      "item": [
        {
          "id": "ac92d474-6078-40ef-a4a2-a5cf70de05fb",
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
              "id": "32049a95-af12-42e5-abf3-4ba7b3c95e99"
            }
          ]
        },
        {
          "id": "da68aaec-c4bc-403c-a0b9-0dc4a0c33a96",
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
              "id": "dbc92271-94f6-4806-bdb5-9bd82b0f02b0"
            }
          ]
        }
      ]
    },
    {
      "name": "Redirect",
      "item": [
        {
          "id": "4d42cc59-94f8-411e-b72d-6acac4134985",
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
              "id": "9f9910c3-f408-43a9-af08-ee3ee7c64cf8"
            }
          ]
        },
        {
          "id": "6364e5ef-6fde-4768-af96-587be9ba5e47",
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
              "id": "1e13189b-8f04-47e4-91e2-ddb802d11009"
            }
          ]
        },
        {
          "id": "bf98af82-8a45-4d61-ac98-905e3c494659",
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
              "id": "fea97a1c-d12b-467e-a3a4-75fe0558eda7"
            }
          ]
        },
        {
          "id": "3e57256c-538b-4e42-a5c0-bf1a66d76149",
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
              "id": "da4a3eb0-1515-496f-99d6-a5961a28b829"
            }
          ]
        }
      ]
    },
    {
      "name": "Datasets",
      "item": [
        {
          "id": "06dccddf-49b9-4b19-821b-321f418c55a8",
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
              "id": "91e46557-646e-49dc-b9b5-e7d93a34524d"
            }
          ]
        }
      ]
    },
    {
      "name": "Look",
      "item": [
        {
          "id": "a0ac9e41-1f2f-49c1-8770-9c11216b8757",
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
              "id": "61cb4c84-a006-454e-9f64-28f65623edad"
            }
          ]
        }
      ]
    },
    {
      "name": "Folder",
      "item": [
        {
          "id": "448f3dbd-8855-4f07-aa0b-0dca4397827c",
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
              "id": "41195a16-4b55-4bb4-9bcc-166d7ea37cd5"
            }
          ]
        }
      ]
    },
    {
      "name": "GCMD",
      "item": [
        {
          "id": "95861797-5c4c-4fc1-bd98-2fa0589ba684",
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
              "id": "79824a69-a2bc-4a16-b007-a5f4f0b7faf2"
            }
          ]
        }
      ]
    },
    {
      "name": "Generic",
      "item": [
        {
          "id": "d79beeb4-88d8-408d-830f-d10bb9c50f61",
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
              "id": "5b53db17-05f7-4d23-a522-4f161767dd8e"
            }
          ]
        }
      ]
    },
    {
      "name": "Images",
      "item": [
        {
          "id": "69fb8a16-02ab-4990-9b80-fbee0672f7be",
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
              "id": "b48b1a8a-6b45-4b87-8a4d-87170bb413d5"
            }
          ]
        }
      ]
    },
    {
      "name": "Instruments",
      "item": [
        {
          "id": "572c7080-fee3-4c27-84e2-cdc1f2e2310a",
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
              "id": "ed156b9a-0967-4b12-8b8c-454d0a2296ab"
            }
          ]
        },
        {
          "id": "3ce6e7f6-0143-4b84-80dd-9f914ba1f4ef",
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
              "id": "aec95af2-867f-4b34-8362-98c5b2ac14c0"
            }
          ]
        }
      ]
    },
    {
      "name": "Journals",
      "item": [
        {
          "id": "89d03132-4f25-49d2-a240-619c8f448a71",
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
              "id": "d46a892a-3bd5-4c6b-b0e7-e16b52a14b30"
            }
          ]
        }
      ]
    },
    {
      "name": "Lexicons",
      "item": [
        {
          "id": "804773bc-bd52-4ad0-a904-9cf249083a63",
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
              "id": "86bd61ca-b1c6-4e71-9854-240fddaa5bb2"
            }
          ]
        }
      ]
    },
    {
      "name": "Lookup",
      "item": [
        {
          "id": "56b5f5a7-ce9b-4d4f-8fd8-ceae48914f7f",
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
              "id": "bd3fafda-6289-44d1-b922-ffe2e51ca6a4"
            }
          ]
        },
        {
          "id": "1861f18b-eb54-4ceb-a793-3e0e501d789b",
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
              "id": "d8891e91-4683-404c-afa2-811141ee710b"
            }
          ]
        }
      ]
    },
    {
      "name": "Terms",
      "item": [
        {
          "id": "be777fa3-bb2b-4627-af6b-391ea457babc",
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
              "id": "0dafd226-7687-446b-b979-cb03ee63e430"
            }
          ]
        }
      ]
    },
    {
      "name": "Overall",
      "item": [
        {
          "id": "be762ebc-f77d-4851-bbeb-5420e65f5cf6",
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
              "id": "60a21014-ac56-4995-b9db-4ebdec6b8941"
            }
          ]
        }
      ]
    },
    {
      "name": "Models",
      "item": [
        {
          "id": "bb456692-279c-401d-aebb-73af85db2ac5",
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
              "id": "8e8a984d-a17b-4c92-a43e-50a84423ecda"
            }
          ]
        }
      ]
    },
    {
      "name": "Model",
      "item": [
        {
          "id": "83fa82f2-ebb2-44da-9894-0fdb9f6cece9",
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
              "id": "bd1617f4-1050-4171-bff8-7cd3a9711ff6"
            }
          ]
        },
        {
          "id": "af2acde1-2573-4783-aadb-46a1550e0bfd",
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
              "id": "b4199ed5-d82a-41d9-8c24-c6bfa15ccb7c"
            }
          ]
        }
      ]
    },
    {
      "name": "Organizations",
      "item": [
        {
          "id": "92468206-a2c5-4044-957e-309394eec0f9",
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
              "id": "6e1ac1ee-2511-430f-910f-89738fc992bd"
            }
          ]
        }
      ]
    },
    {
      "name": "Show",
      "item": [
        {
          "id": "f334a347-264c-4654-b6a6-4c1a24cbcd43",
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
              "id": "217e4b0d-ac34-45cf-8ad3-80a2fe61f0fc"
            }
          ]
        },
        {
          "id": "0213391c-d3f7-4a1b-814d-45a85bf39446",
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
              "id": "9ebe6cee-4b9b-478b-9b6c-5248daaf3b02"
            }
          ]
        }
      ]
    },
    {
      "name": "People",
      "item": [
        {
          "id": "3f91fa6e-b3d5-42f8-8a23-5780882b3976",
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
              "id": "81c2c8b5-6e06-409f-9abf-2bdf8ec795b7"
            }
          ]
        }
      ]
    },
    {
      "name": "Platforms",
      "item": [
        {
          "id": "b678ec9f-3f08-47d4-ae73-fa4a7473b176",
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
              "id": "29d7ed3a-ece5-4d48-b1c4-e0532b2d0f4d"
            }
          ]
        }
      ]
    },
    {
      "name": "Projects",
      "item": [
        {
          "id": "fb01ff4d-8315-4ffd-b05a-d6a64bf8cd22",
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
              "id": "90289cdb-2e5c-4f62-bf44-2d8163d9b180"
            }
          ]
        }
      ]
    },
    {
      "name": "References",
      "item": [
        {
          "id": "a7b28c6e-f151-4605-ad4e-0020e12465e3",
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
              "id": "018257ae-7645-4f4d-a6d1-9411f471a442"
            }
          ]
        }
      ]
    },
    {
      "name": "Regions",
      "item": [
        {
          "id": "14525ad1-8890-429d-854a-30c76d750618",
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
              "id": "9b9d5aba-5f7d-4645-862a-55c819fef8eb"
            }
          ]
        }
      ]
    },
    {
      "name": "Reports",
      "item": [
        {
          "id": "7dafb1e6-37ba-469a-a33d-659bdaa9b0ca",
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
              "id": "488dc426-9fdd-4109-ab18-42b20d78c1f9"
            }
          ]
        }
      ]
    },
    {
      "name": "Chapters",
      "item": [
        {
          "id": "90a35453-009d-4f16-a84f-d9da6ca7abba",
          "name": "get-a-list-of-chapters-in-a-report",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "report/:report_identifier/chapter"
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
            "description": "Get a list of chapters in a report."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8621ba4d-854d-4972-b342-32017bfce6b6"
            }
          ]
        }
      ]
    }
  ]
}