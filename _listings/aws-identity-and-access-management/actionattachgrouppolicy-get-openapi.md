---
swagger: "2.0"
x-collection-name: AWS Identity and Access Management
x-complete: 0
info:
  title: AWS Identity and Access Management API Attach Group Policy
  version: 1.0.0
  description: Attaches the specified managed policy to the specified IAM group.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AddClientIDToOpenIDConnectProvider:
    get:
      summary: Add Client I D To Open I D Connect Provider
      description: |-
        Adds a new client ID (also known as audience) to the list of client IDs already
              registered for the specified IAM OpenID Connect (OIDC) provider resource.
      operationId: addClientIDToOpenIDConnectProvider
      x-api-path-slug: actionaddclientidtoopenidconnectprovider-get
      parameters:
      - in: query
        name: ClientID
        description: The client ID (also known as audience) to add to the IAM OpenID
          Connect provider      resource
        type: string
      - in: query
        name: OpenIDConnectProviderArn
        description: The Amazon Resource Name (ARN) of the IAM OpenID Connect (OIDC)
          provider resource to      add the client ID to
        type: string
      responses:
        200:
          description: OK
      tags:
      - OpenID Connect Providers
  /?Action=AddRoleToInstanceProfile:
    get:
      summary: Add Role To Instance Profile
      description: Adds the specified IAM role to the specified instance profile.
      operationId: addRoleToInstanceProfile
      x-api-path-slug: actionaddroletoinstanceprofile-get
      parameters:
      - in: query
        name: InstanceProfileName
        description: The name of the instance profile to update
        type: string
      - in: query
        name: RoleName
        description: The name of the role to add
        type: string
      responses:
        200:
          description: OK
      tags:
      - Role Instance
  /?Action=AddUserToGroup:
    get:
      summary: Add User To Group
      description: Adds the specified user to the specified group.
      operationId: addUserToGroup
      x-api-path-slug: actionaddusertogroup-get
      parameters:
      - in: query
        name: GroupName
        description: The name of the group to update
        type: string
      - in: query
        name: UserName
        description: The name of the user to add
        type: string
      responses:
        200:
          description: OK
      tags:
      - User Groups
  /?Action=AttachGroupPolicy:
    get:
      summary: Attach Group Policy
      description: Attaches the specified managed policy to the specified IAM group.
      operationId: attachGroupPolicy
      x-api-path-slug: actionattachgrouppolicy-get
      parameters:
      - in: query
        name: GroupName
        description: The name (friendly name, not ARN) of the group to attach the
          policy to
        type: string
      - in: query
        name: PolicyArn
        description: The Amazon Resource Name (ARN) of the IAM policy you want to
          attach
        type: string
      responses:
        200:
          description: OK
      tags:
      - Group Policies
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