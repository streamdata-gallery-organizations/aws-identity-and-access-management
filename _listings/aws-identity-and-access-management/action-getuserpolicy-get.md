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
  /?Action=GetUserPolicy:
    get:
      summary: ' Get User Policy '
      description: |-
        Retrieves the specified inline policy document that is embedded in the specified IAM
              user
      operationId: getUserPolicy
      parameters:
      - in: query
        name: PolicyName
        description: The name of the policy document to get
        type: string
      - in: query
        name: UserName
        description: The name of the user who the policy is associated with
        type: string
      responses:
        200:
          description: OK
      tags:
      - user policies
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