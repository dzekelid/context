swagger: "2.0"
x-collection-name: GlobalChange.gov
x-complete: 1
info:
  title: Global Change Information System API
  description: who-we-are-what-the-gcis-is-and-how-we-use-identifiers-and-semantic-information-to-provide-points-of-reference-and-traceability--examples-and-tutorials-for-using-this-system-as-a-researcher-citizen-scientist-application-developer-or-information-theorist--a-description-of-how-the-information-is-structured-including-the-overlaps-between-relational-and-semantic-representations-of-the-information--complete-documentation-for-the-api-including-methods-for-browsing-and-finding-resources-
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