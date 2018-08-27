---
swagger: "2.0"
x-collection-name: Context.IO
x-complete: 0
info:
  title: Context.IO Get Accounts Messages Message Flags
  description: 'Lists message flags for an account. On-demand data retrieval: to ensure
    up-to-date values, flags are not cached by Context.IO. This call triggers a connection
    to the IMAP server to fetch the current message flags before it returns.'
  version: 1.0.0
host: api.context.io
basePath: /2.0/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /accounts/{id}/messages/{message_id}/flags:
    get:
      summary: Get Accounts Messages Message Flags
      description: 'Lists message flags for an account. On-demand data retrieval:
        to ensure up-to-date values, flags are not cached by Context.IO. This call
        triggers a connection to the IMAP server to fetch the current message flags
        before it returns.'
      operationId: listAccountMessageFlags_
      x-api-path-slug: accountsidmessagesmessage-idflags-get
      parameters:
      - in: path
        name: id
        description: Unique id of an account accessible through your API key
      - in: path
        name: message_id
        description: Unique id of a message
      responses:
        200:
          description: OK
      tags:
      - Accounts
      - Messages
      - Message
      - Flags
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