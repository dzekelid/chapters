---
swagger: "2.0"
x-collection-name: GlobalChange.gov
x-complete: 0
info:
  title: Global Change Information System API List tables in a chapter
  description: Get a list of tables in a chapter.
  version: v1
host: data.globalchange.gov
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /report/{report_identifier}/chapter:
    get:
      summary: List chapters in a report
      description: Get a list of chapters in a report.
      operationId: get-a-list-of-chapters-in-a-report
      x-api-path-slug: reportreport-identifierchapter-get
      parameters:
      - in: query
        name: all
        description: Set to 1 to get all of the chapters
      - in: query
        name: page
        description: The page number (starting at 1)
      - in: path
        name: report_identifier
        description: report_identifier description
      responses:
        200:
          description: OK
      tags:
      - Chapters
      - Report
  /report/{report_identifier}/chapter/{chapter_identifier}:
    get:
      summary: Get a representation of a chapter.
      description: Get JSON which represents the structure of a chapter.
      operationId: get-json-which-represents-the-structure-of-a-chapter
      x-api-path-slug: reportreport-identifierchapterchapter-identifier-get
      parameters:
      - in: path
        name: chapter_identifier
        description: chapter_identifier description
      - in: path
        name: ids
        description: '{ids} can contain up to 100 semicolon delimited ids, to find
          ids programatically look for answer_id on answer objects'
      - in: path
        name: report_identifier
        description: report_identifier description
      - in: query
        name: with_gcmd
        description: Include GCMD keywords associated with the chapter
      - in: query
        name: with_regions
        description: Include regions associated with the chapter
      responses:
        200:
          description: OK
      tags:
      - Representation
      - Chapter
  /report/{report_identifier}/chapter/{chapter_identifier}/figure:
    get:
      summary: List figures in a chapter
      description: Get a list of figures in a chapter.
      operationId: get-a-list-of-figures-in-a-chapter
      x-api-path-slug: reportreport-identifierchapterchapter-identifierfigure-get
      parameters:
      - in: query
        name: all
        description: Set to 1 to get all of the figures
      - in: path
        name: chapter_identifier
        description: chapter_identifier description
      - in: path
        name: ids
        description: '{ids} can contain up to 100 semicolon delimited ids, to find
          ids programatically look for answer_id on answer objects'
      - in: query
        name: page
        description: The page number (starting at 1)
      - in: path
        name: report_identifier
        description: report_identifier description
      responses:
        200:
          description: OK
      tags:
      - Figures
      - Chapter
  /report/{report_identifier}/chapter/{chapter_identifier}/figure/{figure_identifier}:
    get:
      summary: Get a representation of a figure in a chapter.
      description: Get JSON which represents the structure of a figure in a chapter.
      operationId: get-json-which-represents-the-structure-of-a-figure-in-a-chapter
      x-api-path-slug: reportreport-identifierchapterchapter-identifierfigurefigure-identifier-get
      parameters:
      - in: path
        name: chapter_identifier
        description: chapter_identifier description
      - in: path
        name: figure_identifier
        description: figure_identifier description
      - in: path
        name: ids
        description: '{ids} can contain up to 100 semicolon delimited ids, to find
          ids programatically look for answer_id on answer objects'
      - in: path
        name: report_identifier
        description: report_identifier description
      - in: query
        name: with_gcmd
        description: Include GCMD keywords associated with the figure
      - in: query
        name: with_regions
        description: Include regions associated with the figure
      responses:
        200:
          description: OK
      tags:
      - Representation
      - Figure
      - Chapter
  /report/{report_identifier}/chapter/{chapter_identifier}/finding:
    get:
      summary: List findings in a chapter
      description: Get a list of findings in a chapter.
      operationId: get-a-list-of-findings-in-a-chapter
      x-api-path-slug: reportreport-identifierchapterchapter-identifierfinding-get
      parameters:
      - in: query
        name: all
        description: Set to 1 to get all of the findings
      - in: path
        name: chapter_identifier
        description: chapter_identifier description
      - in: path
        name: ids
        description: '{ids} can contain up to 100 semicolon delimited ids, to find
          ids programatically look for answer_id on answer objects'
      - in: query
        name: page
        description: The page number (starting at 1)
      - in: path
        name: report_identifier
        description: report_identifier description
      responses:
        200:
          description: OK
      tags:
      - Findings
      - Chapter
  /report/{report_identifier}/chapter/{chapter_identifier}/finding/{finding_identifier}:
    get:
      summary: Get a representation of a finding in a chapter.
      description: Get JSON which represents the structure of a finding in a chapter.
      operationId: get-json-which-represents-the-structure-of-a-finding-in-a-chapter
      x-api-path-slug: reportreport-identifierchapterchapter-identifierfindingfinding-identifier-get
      parameters:
      - in: path
        name: chapter_identifier
        description: chapter_identifier description
      - in: path
        name: finding_identifier
        description: finding_identifier description
      - in: path
        name: report_identifier
        description: report_identifier description
      - in: query
        name: with_gcmd
        description: Include GCMD keywords associated with the finding
      - in: query
        name: with_regions
        description: Include regions associated with the finding
      responses:
        200:
          description: OK
      tags:
      - Representation
      - Finding
      - Chapter
  /report/{report_identifier}/chapter/{chapter_identifier}/reference:
    get:
      summary: List references in a chapter
      description: Get a list of references in a chapter.
      operationId: get-a-list-of-references-in-a-chapter
      x-api-path-slug: reportreport-identifierchapterchapter-identifierreference-get
      parameters:
      - in: query
        name: all
        description: Set to 1 to get all of the references
      - in: path
        name: chapter_identifier
        description: chapter_identifier description
      - in: query
        name: page
        description: The page number (starting at 1)
      - in: path
        name: report_identifier
        description: report_identifier description
      responses:
        200:
          description: OK
      tags:
      - References
      - Chapter
  /report/{report_identifier}/chapter/{chapter_identifier}/table:
    get:
      summary: List tables in a chapter
      description: Get a list of tables in a chapter.
      operationId: get-a-list-of-tables-in-a-chapter
      x-api-path-slug: reportreport-identifierchapterchapter-identifiertable-get
      parameters:
      - in: query
        name: all
        description: Set to 1 to get all of the tables
      - in: path
        name: chapter_identifier
        description: chapter_identifier description
      - in: query
        name: page
        description: The page number (starting at 1)
      - in: path
        name: report_identifier
        description: report_identifier description
      responses:
        200:
          description: OK
      tags:
      - Tables
      - Chapter
  /report/{report_identifier}/chapter/{chapter_identifier}/table/{table_identifier}:
    get:
      summary: Get a representation of a table in a chapter.
      description: Get JSON which represents the structure of a table in a chapter.
      operationId: get-json-which-represents-the-structure-of-a-table-in-a-chapter
      x-api-path-slug: reportreport-identifierchapterchapter-identifiertabletable-identifier-get
      parameters:
      - in: path
        name: chapter_identifier
        description: chapter_identifier description
      - in: path
        name: report_identifier
        description: report_identifier description
      - in: path
        name: table_identifier
        description: table_identifier description
      - in: query
        name: with_gcmd
        description: Include GCMD keywords associated with the table
      - in: query
        name: with_regions
        description: Include regions associated with the table
      responses:
        200:
          description: OK
      tags:
      - Representation
      - Table
      - Chapter
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