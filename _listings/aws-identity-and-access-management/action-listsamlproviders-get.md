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
  /?Action=ListSAMLProviders:
    get:
      summary: ' List S A M L Providers '
      description: Lists the SAML provider resource objects defined in IAM in the
        account
      operationId: listSAMLProviders
      parameters:
      - in: query
        name: SAMLProviderList.member.N
        description: The list of SAML provider resource objects defined in IAM for
          this AWS      account
        type: string
      responses:
        200:
          description: OK
      tags:
      - saml providers
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