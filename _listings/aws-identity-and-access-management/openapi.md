---
swagger: "2.0"
x-collection-name: AWS Identity and Access Management
x-complete: 1
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
      summary: Get Context Keys For Custom Policy
      description: Gets a list of all of the context keys referenced in the input
        policies.
      operationId: getContextKeysForCustomPolicy
      x-api-path-slug: actiongetcontextkeysforcustompolicy-get
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
      - Context Keys For Custom Policies
  /?Action=GetContextKeysForPrincipalPolicy:
    get:
      summary: Get Context Keys For Principal Policy
      description: |-
        Gets a list of all of the context keys referenced in all of the IAM policies attached
              to the specified IAM entity.
      operationId: getContextKeysForPrincipalPolicy
      x-api-path-slug: actiongetcontextkeysforprincipalpolicy-get
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
      - Context Keys For Principal Policies
---