---
swagger: "2.0"
x-collection-name: Stride
x-complete: 1
info:
  title: Stride
  description: this-service-provides-public-api-for-the-stride-
  version: 1.0.0
host: api.atlassian.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /site/{cloudId}/conversation/{conversationId}/message/{messageId}/context:
    get:
      summary: Get conversation history contextually
      description: |-
        Authentication required, with scope participate:conversation

        This method returns messages after and/or before a given messageID including the message itself.
        Default value for 'after' and 'before' query parameters is 0.
      operationId: SiteConversationMessageMessageIdContextByCloudIdAndConversationIdGet
      x-api-path-slug: sitecloudidconversationconversationidmessagemessageidcontext-get
      parameters:
      - in: header
        name: Accept
      - in: query
        name: after
      - in: query
        name: before
      - in: path
        name: cloudId
      - in: header
        name: Content-Type
      - in: path
        name: conversationId
      - in: path
        name: messageId
      responses:
        200:
          description: OK
      tags:
      - Messaging
      - Site
      - Cloud
      - Conversation
      - Conversation
      - Message
      - Message
      - Context
---