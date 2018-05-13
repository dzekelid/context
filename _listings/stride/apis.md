---
name: Stride
description: Stride is a cloud-based team business communication and collaboration
  tool, launched by Atlassian to replace the cloud-based version of HipChat. Stride
  software is available to download onto computers running Windows, Mac or Linux,
  as well as Android, iOS smartphones, and tablets
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/atlassian-stride-logo.jpg
x-kinRank: "8"
x-alexaRank: ""
tags:
- Messaging
- Chat
created: "2018-03-23"
modified: "2018-03-23"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/context/master/_listings/stride/apis.yaml
specificationVersion: "0.14"
apis:
- name: Stride
  description: Stride is a cloud-based team business communication and collaboration
    tool, launched by Atlassian to replace the cloud-based version of HipChat
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/atlassian-stride-logo.jpg
  humanURL: ""
  baseURL: https://api.atlassian.com//
  tags: Context
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/context/master/_listings/stride/site-cloudid-conversation-conversationid-message-messageid-context-get.md
- name: Stride Get conversation history contextually
  description: |-
    Authentication required, with scope participate:conversation

    This method returns messages after and/or before a given messageID including the message itself.
    Default value for 'after' and 'before' query parameters is 0.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/atlassian-stride-logo.jpg
  humanURL: https://www.stride.com/
  baseURL: https://api.atlassian.com//
  tags: Context
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/context/master/_listings/stride/site-cloudid-conversation-conversationid-message-messageid-context-get.md
x-common:
- type: x-authentication
  url: https://developer.atlassian.com/cloud/stride/security/authentication/
- type: x-blog
  url: https://blog.stride.com/
- type: x-buttons
  url: https://developer.atlassian.com/cloud/stride/blocks/stride-button/
- type: x-developer
  url: https://developer.atlassian.com/cloud/stride/
- type: x-getting-started
  url: https://developer.atlassian.com/cloud/stride/getting-started/
- type: x-pricing
  url: https://www.stride.com/pricing
- type: x-security
  url: https://developer.atlassian.com/cloud/stride/security/security-overview/
- type: x-support
  url: https://www.stride.com/help-center
- type: x-twitter
  url: https://twitter.com/atlassianstride
- type: x-website
  url: https://www.stride.com/
- type: x-authentication
  url: https://developer.atlassian.com/cloud/stride/security/authentication/
- type: x-blog
  url: https://blog.stride.com/
- type: x-buttons
  url: https://developer.atlassian.com/cloud/stride/blocks/stride-button/
- type: x-developer
  url: https://developer.atlassian.com/cloud/stride/
- type: x-getting-started
  url: https://developer.atlassian.com/cloud/stride/getting-started/
- type: x-pricing
  url: https://www.stride.com/pricing
- type: x-security
  url: https://developer.atlassian.com/cloud/stride/security/security-overview/
- type: x-support
  url: https://www.stride.com/help-center
- type: x-twitter
  url: https://twitter.com/atlassianstride
- type: x-website
  url: https://www.stride.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---