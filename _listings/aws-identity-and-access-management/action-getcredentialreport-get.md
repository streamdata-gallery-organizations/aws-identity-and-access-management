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
  /?Action=GetCredentialReport:
    get:
      summary: ' Get Credential Report '
      description: Retrieves a credential report for the AWS account
      operationId: getCredentialReport
      parameters:
      - in: query
        name: Content
        description: Contains the credential report
        type: string
      - in: query
        name: GeneratedTime
        description: The date and time when the credential report was created, in
          ISO 8601 date-time format
        type: string
      - in: query
        name: ReportFormat
        description: The format (MIME type) of the credential report
        type: string
      responses:
        200:
          description: OK
      tags:
      - credential reports
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