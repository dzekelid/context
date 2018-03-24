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
  /?Action=GetContextKeysForPrincipalPolicy:
    get:
      summary: ' Get Context Keys For Principal Policy '
      description: |-
        Gets a list of all of the context keys referenced in all of the IAM policies attached
              to the specified IAM entity
      operationId: getContextKeysForPrincipalPolicy
      parameters:
      - in: query
        name: PolicyInputList.member.N
        description: An optional list of additional policies for which you want the
          list of context keys      that are referenced
        type: string
      - in: query
        name: PolicySourceArn
        description: The ARN of a user, group, or role whose policies contain the
          context keys that you want      listed
        type: string
      responses:
        200:
          description: OK
      tags:
      - context keys for principal policies
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