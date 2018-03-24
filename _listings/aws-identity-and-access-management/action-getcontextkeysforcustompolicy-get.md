---
swagger: "2.0"
info:
  title: AWS Identity and Access Management API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=GetContextKeysForCustomPolicy:
    get:
      summary: ' Get Context Keys For Custom Policy '
      description: Gets a list of all of the context keys referenced in the input
        policies
      operationId: getContextKeysForCustomPolicy
      parameters:
      - in: query
        name: PolicyInputList.member.N
        description: A list of policies for which you want the list of context keys
          referenced in those      policies
        type: string
      responses:
        200:
          description: OK
      tags:
      - context keys for custom policies
definitions: []
x-collection-name: AWS Identity and Access Management
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