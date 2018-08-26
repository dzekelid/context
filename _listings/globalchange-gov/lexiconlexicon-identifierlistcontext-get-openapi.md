---
swagger: "2.0"
x-collection-name: GlobalChange.gov
x-complete: 0
info:
  title: Global Change Information System API List the terms within a context of a
    lexicon
  description: List the terms within a context of a lexicon
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
  /lexicon/{lexicon_identifier}/list/{context}:
    get:
      summary: List the terms within a context of a lexicon
      description: List the terms within a context of a lexicon
      operationId: list-the-terms-within-a-context-of-a-lexicon
      x-api-path-slug: lexiconlexicon-identifierlistcontext-get
      parameters:
      - in: path
        name: context
        description: context description
      - in: path
        name: lexicon_identifier
        description: lexicon_identifier description
      responses:
        200:
          description: OK
      tags:
      - Terms
      - Within
      - Context
      - Lexicon
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