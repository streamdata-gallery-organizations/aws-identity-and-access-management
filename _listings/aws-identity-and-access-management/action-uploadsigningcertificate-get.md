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
  /?Action=UploadSigningCertificate:
    get:
      summary: ' Upload Signing Certificate '
      description: Uploads an X
      operationId: uploadSigningCertificate
      parameters:
      - in: query
        name: CertificateBody
        description: The contents of the signing certificate
        type: string
      - in: query
        name: UserName
        description: The name of the user the signing certificate is for
        type: string
      responses:
        200:
          description: OK
      tags:
      - signing certificates
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