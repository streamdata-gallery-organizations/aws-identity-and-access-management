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
  /?Action=UploadServerCertificate:
    get:
      summary: ' Upload Server Certificate '
      description: Uploads a server certificate entity for the AWS account
      operationId: uploadServerCertificate
      parameters:
      - in: query
        name: CertificateBody
        description: The contents of the public key certificate in PEM-encoded format
        type: string
      - in: query
        name: CertificateChain
        description: The contents of the certificate chain
        type: string
      - in: query
        name: Path
        description: The path for the server certificate
        type: string
      - in: query
        name: PrivateKey
        description: The contents of the private key in PEM-encoded format
        type: string
      - in: query
        name: ServerCertificateName
        description: The name for the server certificate
        type: string
      responses:
        200:
          description: OK
      tags:
      - server certificates
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