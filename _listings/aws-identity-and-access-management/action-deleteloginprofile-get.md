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
  /?Action=DeleteLoginProfile&k=1:
    get:
      summary: ' Delete Login Profile '
      description: |-
        Deletes the password for the specified IAM user, which terminates the user's ability
              to access AWS services through the AWS Management Console
      operationId: deleteLoginProfile
      parameters:
      - in: query
        name: UserName
        description: The name of the user whose password you want to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - login profiles
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