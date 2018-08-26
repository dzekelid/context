---
swagger: "2.0"
x-collection-name: Context.IO
x-complete: 1
info:
  title: Context.IO
  description: context-io-is-the-missing-email-api-that-makes-it-easy-and-fast-to-integrate-your-users-email-data-in-your-application-
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
---