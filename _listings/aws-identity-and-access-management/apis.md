---
name: AWS Identity and Access Management
x-slug: aws-identity-and-access-management
description: AWS Identity and Access Management (IAM) enables you to securely control
  access to AWS services and resources for your users. Using IAM, you can create and
  manage AWS users and groups, and use permissions to allow and deny their access
  to AWS resources.IAM is a feature of your AWS account offered at no additional charge.
  You will be charged only for use of other AWS services by your users.To get started
  using IAM, orif you have already registered with AWS, go to theAWS Management Consoleand
  get started with theseIAM Best Practices.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
x-kinRank: "10"
x-alexaRank: ""
tags: AWS Identity and Access Management
created: "2018-05-24"
modified: "2018-05-24"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Identity and Access Management API Add Client I D To Open I D Connect
    Provider
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Adds a new client ID (also known as audience) to the list of client IDs already
          registered for the specified IAM OpenID Connect (OIDC) provider resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=AddClientIDToOpenIDConnectProvider
  tags: OpenID Connect Providers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionaddclientidtoopenidconnectprovider-get-openapi.md
- name: AWS Identity and Access Management API Add Role To Instance Profile
  x-api-slug: aws-identity-and-access-management-api
  description: Adds the specified IAM role to the specified instance profile.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=AddRoleToInstanceProfile
  tags: Role Instance
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionaddroletoinstanceprofile-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionaddroletoinstanceprofile-get-openapi.md
- name: AWS Identity and Access Management API Add User To Group
  x-api-slug: aws-identity-and-access-management-api
  description: Adds the specified user to the specified group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=AddUserToGroup
  tags: User Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionaddusertogroup-get-openapi.md
- name: AWS Identity and Access Management API Attach Group Policy
  x-api-slug: aws-identity-and-access-management-api
  description: Attaches the specified managed policy to the specified IAM group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=AttachGroupPolicy
  tags: Group Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionattachgrouppolicy-get-openapi.md
- name: AWS Identity and Access Management API Attach Role Policy
  x-api-slug: aws-identity-and-access-management-api
  description: Attaches the specified managed policy to the specified IAM role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=AttachRolePolicy
  tags: Role Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionattachrolepolicy-get-openapi.md
- name: AWS Identity and Access Management API Attach User Policy
  x-api-slug: aws-identity-and-access-management-api
  description: Attaches the specified managed policy to the specified user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=AttachUserPolicy
  tags: User Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionattachuserpolicy-get-openapi.md
- name: AWS Identity and Access Management API Change Password
  x-api-slug: aws-identity-and-access-management-api
  description: Changes the password of the IAM user who is calling this action.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=ChangePassword
  tags: Passwords
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionchangepassword-get-openapi.md
- name: AWS Identity and Access Management API Create Access Key
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Creates a new AWS secret access key and corresponding AWS access key ID for the
          specified user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=CreateAccessKey
  tags: Access Keys
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actioncreateaccesskey-get-openapi.md
- name: AWS Identity and Access Management API Create Account Alias
  x-api-slug: aws-identity-and-access-management-api
  description: Creates an alias for your AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=CreateAccountAlias
  tags: Account Alias
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actioncreateaccountalias-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actioncreateaccountalias-get-openapi.md
- name: AWS Identity and Access Management API Create Group
  x-api-slug: aws-identity-and-access-management-api
  description: Creates a new group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=CreateGroup
  tags: Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actioncreategroup-get-openapi.md
- name: AWS Identity and Access Management API Create Instance Profile
  x-api-slug: aws-identity-and-access-management-api
  description: Creates a new instance profile.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=CreateInstanceProfile
  tags: Instance Profiles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actioncreateinstanceprofile-get-openapi.md
- name: AWS Identity and Access Management API Create Login Profile
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Creates a password for the specified user, giving the user the ability to access AWS
          services through the AWS Management Console.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=CreateLoginProfile
  tags: Login Profiles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actioncreateloginprofile-get-openapi.md
- name: AWS Identity and Access Management API Create Open I D Connect Provider
  x-api-slug: aws-identity-and-access-management-api
  description: Creates an IAM entity to describe an identity provider (IdP) that supports.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=CreateOpenIDConnectProvider
  tags: OpenID Connect Providers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actioncreateopenidconnectprovider-get-openapi.md
- name: AWS Identity and Access Management API Create Policy
  x-api-slug: aws-identity-and-access-management-api
  description: Creates a new managed policy for your AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=CreatePolicy
  tags: Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actioncreatepolicy-get-openapi.md
- name: AWS Identity and Access Management API Create Policy Version
  x-api-slug: aws-identity-and-access-management-api
  description: Creates a new version of the specified managed policy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=CreatePolicyVersion
  tags: Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actioncreatepolicyversion-get-openapi.md
- name: AWS Identity and Access Management API Create Role
  x-api-slug: aws-identity-and-access-management-api
  description: Creates a new role for your AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=CreateRole
  tags: Roles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actioncreaterole-get-openapi.md
- name: AWS Identity and Access Management API Create S A M L Provider
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Creates an IAM resource that describes an identity provider (IdP) that supports SAML
          2.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=CreateSAMLProvider
  tags: SAML Providers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actioncreatesamlprovider-get-openapi.md
- name: AWS Identity and Access Management API Create Service Specific Credential
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Generates a set of credentials consisting of a user name and password that can be used
          to access the service specified in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=CreateServiceSpecificCredential
  tags: Service Specific Credentials
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actioncreateservicespecificcredential-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actioncreateservicespecificcredential-get-openapi.md
- name: AWS Identity and Access Management API Create User
  x-api-slug: aws-identity-and-access-management-api
  description: Creates a new IAM user for your AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=CreateUser
  tags: Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actioncreateuser-get-openapi.md
- name: AWS Identity and Access Management API Create Virtual M F A Device
  x-api-slug: aws-identity-and-access-management-api
  description: Creates a new virtual MFA device for the AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=CreateVirtualMFADevice
  tags: Virtual MFA Device
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actioncreatevirtualmfadevice-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actioncreatevirtualmfadevice-get-openapi.md
- name: AWS Identity and Access Management API Deactivate M F A Device
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Deactivates the specified MFA device and removes it from association with the user name
          for which it was originally enabled.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=DeactivateMFADevice
  tags: Virtual MFA Device
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiondeactivatemfadevice-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiondeactivatemfadevice-get-openapi.md
- name: AWS Identity and Access Management API Delete Access Key
  x-api-slug: aws-identity-and-access-management-api
  description: Deletes the access key pair associated with the specified IAM user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=DeleteAccessKey
  tags: Access Keys
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiondeleteaccesskey-get-openapi.md
- name: AWS Identity and Access Management API Delete Account Alias
  x-api-slug: aws-identity-and-access-management-api
  description: Deletes the specified AWS account alias.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=DeleteAccountAlias
  tags: Account Alias
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiondeleteaccountalias-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiondeleteaccountalias-get-openapi.md
- name: AWS Identity and Access Management API Delete Account Password Policy
  x-api-slug: aws-identity-and-access-management-api
  description: Deletes the password policy for the AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=DeleteAccountPasswordPolicy
  tags: Account Password Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiondeleteaccountpasswordpolicy-get-openapi.md
- name: AWS Identity and Access Management API Delete Group
  x-api-slug: aws-identity-and-access-management-api
  description: Deletes the specified IAM group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=DeleteGroup
  tags: Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiondeletegroup-get-openapi.md
- name: AWS Identity and Access Management API Delete Group Policy
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Deletes the specified inline policy that is embedded in the specified IAM
          group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=DeleteGroupPolicy
  tags: Group Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiondeletegrouppolicy-get-openapi.md
- name: AWS Identity and Access Management API Delete Instance Profile
  x-api-slug: aws-identity-and-access-management-api
  description: Deletes the specified instance profile.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=DeleteInstanceProfile
  tags: Instance Profiles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiondeleteinstanceprofile-get-openapi.md
- name: AWS Identity and Access Management API Delete Login Profile
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Deletes the password for the specified IAM user, which terminates the user's ability
          to access AWS services through the AWS Management Console.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=DeleteLoginProfile
  tags: Login Profiles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiondeleteloginprofile-get-openapi.md
- name: AWS Identity and Access Management API Delete Open I D Connect Provider
  x-api-slug: aws-identity-and-access-management-api
  description: Deletes an OpenID Connect identity provider (IdP) resource object in
    IAM.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=DeleteOpenIDConnectProvider
  tags: OpenID Connect Providers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiondeleteopenidconnectprovider-get-openapi.md
- name: AWS Identity and Access Management API Delete Policy
  x-api-slug: aws-identity-and-access-management-api
  description: Deletes the specified managed policy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=DeletePolicy
  tags: Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiondeletepolicy-get-openapi.md
- name: AWS Identity and Access Management API Delete Policy Version
  x-api-slug: aws-identity-and-access-management-api
  description: Deletes the specified version from the specified managed policy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=DeletePolicyVersion
  tags: Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiondeletepolicyversion-get-openapi.md
- name: AWS Identity and Access Management API Delete Role
  x-api-slug: aws-identity-and-access-management-api
  description: Deletes the specified role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=DeleteRole
  tags: Roles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiondeleterole-get-openapi.md
- name: AWS Identity and Access Management API Delete Role Policy
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Deletes the specified inline policy that is embedded in the specified IAM
          role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=DeleteRolePolicy
  tags: Role Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiondeleterolepolicy-get-openapi.md
- name: AWS Identity and Access Management API Delete S A M L Provider
  x-api-slug: aws-identity-and-access-management-api
  description: Deletes a SAML provider resource in IAM.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=DeleteSAMLProvider
  tags: SAML Providers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiondeletesamlprovider-get-openapi.md
- name: AWS Identity and Access Management API Delete Server Certificate
  x-api-slug: aws-identity-and-access-management-api
  description: Deletes the specified server certificate.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=DeleteServerCertificate
  tags: Server Certificates
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiondeleteservercertificate-get-openapi.md
- name: AWS Identity and Access Management API Delete Service Specific Credential
  x-api-slug: aws-identity-and-access-management-api
  description: Deletes the specified service-specific credential.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=DeleteServiceSpecificCredential
  tags: Service Specific Credentials
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiondeleteservicespecificcredential-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiondeleteservicespecificcredential-get-openapi.md
- name: AWS Identity and Access Management API Delete Signing Certificate
  x-api-slug: aws-identity-and-access-management-api
  description: Deletes a signing certificate associated with the specified IAM user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=DeleteSigningCertificate
  tags: Signing Certificates
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiondeletesigningcertificate-get-openapi.md
- name: AWS Identity and Access Management API Delete S S H Public Key
  x-api-slug: aws-identity-and-access-management-api
  description: Deletes the specified SSH public key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=DeleteSSHPublicKey
  tags: SSH Public Key
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiondeletesshpublickey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiondeletesshpublickey-get-openapi.md
- name: AWS Identity and Access Management API Delete User
  x-api-slug: aws-identity-and-access-management-api
  description: Deletes the specified IAM user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=DeleteUser
  tags: Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiondeleteuser-get-openapi.md
- name: AWS Identity and Access Management API Delete User Policy
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Deletes the specified inline policy that is embedded in the specified IAM
          user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=DeleteUserPolicy
  tags: User Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiondeleteuserpolicy-get-openapi.md
- name: AWS Identity and Access Management API Delete Virtual M F A Device
  x-api-slug: aws-identity-and-access-management-api
  description: Deletes a virtual MFA device.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=DeleteVirtualMFADevice
  tags: Virtual MFA Devices
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiondeletevirtualmfadevice-get-openapi.md
- name: AWS Identity and Access Management API Detach Group Policy
  x-api-slug: aws-identity-and-access-management-api
  description: Removes the specified managed policy from the specified IAM group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=DetachGroupPolicy
  tags: Group Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiondetachgrouppolicy-get-openapi.md
- name: AWS Identity and Access Management API Detach Role Policy
  x-api-slug: aws-identity-and-access-management-api
  description: Removes the specified managed policy from the specified role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=DetachRolePolicy
  tags: Role Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiondetachrolepolicy-get-openapi.md
- name: AWS Identity and Access Management API Detach User Policy
  x-api-slug: aws-identity-and-access-management-api
  description: Removes the specified managed policy from the specified user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=DetachUserPolicy
  tags: User Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiondetachuserpolicy-get-openapi.md
- name: AWS Identity and Access Management API Enable M F A Device
  x-api-slug: aws-identity-and-access-management-api
  description: Enables the specified MFA device and associates it with the specified
    IAM user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=EnableMFADevice
  tags: MFA Devices
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionenablemfadevice-get-openapi.md
- name: AWS Identity and Access Management API Generate Credential Report
  x-api-slug: aws-identity-and-access-management-api
  description: Generates a credential report for the AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=GenerateCredentialReport
  tags: Credential Reports
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiongeneratecredentialreport-get-openapi.md
- name: AWS Identity and Access Management API Get Access Key Last Used
  x-api-slug: aws-identity-and-access-management-api
  description: Retrieves information about when the specified access key was last
    used.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=GetAccessKeyLastUsed
  tags: Access Keys
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiongetaccesskeylastused-get-openapi.md
- name: AWS Identity and Access Management API Get Account Authorization Details
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Retrieves information about all IAM users, groups, roles, and policies in your AWS
          account, including their relationships to one another.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=GetAccountAuthorizationDetails
  tags: Accounts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiongetaccountauthorizationdetails-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiongetaccountauthorizationdetails-get-openapi.md
- name: AWS Identity and Access Management API Get Account Password Policy
  x-api-slug: aws-identity-and-access-management-api
  description: Retrieves the password policy for the AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=GetAccountPasswordPolicy
  tags: Accounts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiongetaccountpasswordpolicy-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiongetaccountpasswordpolicy-get-openapi.md
- name: AWS Identity and Access Management API Get Account Summary
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Retrieves information about IAM entity usage and IAM quotas in the AWS
          account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=GetAccountSummary
  tags: Accounts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiongetaccountsummary-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiongetaccountsummary-get-openapi.md
- name: AWS Identity and Access Management API Get Context Keys For Custom Policy
  x-api-slug: aws-identity-and-access-management-api
  description: Gets a list of all of the context keys referenced in the input policies.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=GetContextKeysForCustomPolicy
  tags: Context Keys For Custom Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiongetcontextkeysforcustompolicy-get-openapi.md
- name: AWS Identity and Access Management API Get Context Keys For Principal Policy
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Gets a list of all of the context keys referenced in all of the IAM policies attached
          to the specified IAM entity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=GetContextKeysForPrincipalPolicy
  tags: Context Keys For Principal Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiongetcontextkeysforprincipalpolicy-get-openapi.md
- name: AWS Identity and Access Management API Get Credential Report
  x-api-slug: aws-identity-and-access-management-api
  description: Retrieves a credential report for the AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=GetCredentialReport
  tags: Credential Reports
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiongetcredentialreport-get-openapi.md
- name: AWS Identity and Access Management API Get Group
  x-api-slug: aws-identity-and-access-management-api
  description: Returns a list of IAM users that are in the specified IAM group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=GetGroup
  tags: Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiongetgroup-get-openapi.md
- name: AWS Identity and Access Management API Get Group Policy
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Retrieves the specified inline policy document that is embedded in the specified IAM
          group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=GetGroupPolicy
  tags: Group Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiongetgrouppolicy-get-openapi.md
- name: AWS Identity and Access Management API Get Instance Profile
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Retrieves information about the specified instance profile, including the instance
          profile's path, GUID, ARN, and role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=GetInstanceProfile
  tags: Instance Profiles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiongetinstanceprofile-get-openapi.md
- name: AWS Identity and Access Management API Get Login Profile
  x-api-slug: aws-identity-and-access-management-api
  description: Retrieves the user name and password-creation date for the specified
    IAM user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=GetLoginProfile
  tags: Login Profiles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiongetloginprofile-get-openapi.md
- name: AWS Identity and Access Management API Get Open I D Connect Provider
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Returns information about the specified OpenID Connect (OIDC) provider resource object
          in IAM.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=GetOpenIDConnectProvider
  tags: OpenID Connect Providers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiongetopenidconnectprovider-get-openapi.md
- name: AWS Identity and Access Management API Get Policy
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Retrieves information about the specified managed policy, including the policy's
          default version and the total number of IAM users, groups, and roles to which the policy is
          attached.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=GetPolicy
  tags: Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiongetpolicy-get-openapi.md
- name: AWS Identity and Access Management API Get Policy Version
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Retrieves information about the specified version of the specified managed policy,
          including the policy document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=GetPolicyVersion
  tags: Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiongetpolicyversion-get-openapi.md
- name: AWS Identity and Access Management API Get Role
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Retrieves information about the specified role, including the role's path, GUID, ARN,
          and the role's trust policy that grants permission to assume the role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=GetRole
  tags: Roles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiongetrole-get-openapi.md
- name: AWS Identity and Access Management API Get Role Policy
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Retrieves the specified inline policy document that is embedded with the specified
          IAM role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=GetRolePolicy
  tags: Role Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiongetrolepolicy-get-openapi.md
- name: AWS Identity and Access Management API Get S A M L Provider
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Returns the SAML provider metadocument that was uploaded when the IAM SAML provider
          resource object was created or updated.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=GetSAMLProvider
  tags: SAML Providers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiongetsamlprovider-get-openapi.md
- name: AWS Identity and Access Management API Get Server Certificate
  x-api-slug: aws-identity-and-access-management-api
  description: Retrieves information about the specified server certificate stored
    in IAM.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=GetServerCertificate
  tags: Server Certificates
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiongetservercertificate-get-openapi.md
- name: AWS Identity and Access Management API Get S S H Public Key
  x-api-slug: aws-identity-and-access-management-api
  description: Retrieves the specified SSH public key, including metadata about the
    key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=GetSSHPublicKey
  tags: SSH Public Key
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiongetsshpublickey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiongetsshpublickey-get-openapi.md
- name: AWS Identity and Access Management API Get User
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Retrieves information about the specified IAM user, including the user's creation
          date, path, unique ID, and ARN.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=GetUser
  tags: Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiongetuser-get-openapi.md
- name: AWS Identity and Access Management API Get User Policy
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Retrieves the specified inline policy document that is embedded in the specified IAM
          user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=GetUserPolicy
  tags: User Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actiongetuserpolicy-get-openapi.md
- name: AWS Identity and Access Management API List Access Keys
  x-api-slug: aws-identity-and-access-management-api
  description: Returns information about the access key IDs associated with the specified
    IAM user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=ListAccessKeys
  tags: Access Keys
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionlistaccesskeys-get-openapi.md
- name: AWS Identity and Access Management API List Account Aliases
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Lists the account alias associated with the AWS account (Note: you can have only
          one).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=ListAccountAliases
  tags: Account Aliases
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionlistaccountaliases-get-openapi.md
- name: AWS Identity and Access Management API List Attached Group Policies
  x-api-slug: aws-identity-and-access-management-api
  description: Lists all managed policies that are attached to the specified IAM group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=ListAttachedGroupPolicies
  tags: Attached Group Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionlistattachedgrouppolicies-get-openapi.md
- name: AWS Identity and Access Management API List Attached Role Policies
  x-api-slug: aws-identity-and-access-management-api
  description: Lists all managed policies that are attached to the specified IAM role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=ListAttachedRolePolicies
  tags: Attached Role Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionlistattachedrolepolicies-get-openapi.md
- name: AWS Identity and Access Management API List Attached User Policies
  x-api-slug: aws-identity-and-access-management-api
  description: Lists all managed policies that are attached to the specified IAM user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=ListAttachedUserPolicies
  tags: Attached Use rPolicies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionlistattacheduserpolicies-get-openapi.md
- name: AWS Identity and Access Management API List Entities For Policy
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Lists all IAM users, groups, and roles that the specified managed policy is attached
          to.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=ListEntitiesForPolicy
  tags: Entities For Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionlistentitiesforpolicy-get-openapi.md
- name: AWS Identity and Access Management API List Group Policies
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Lists the names of the inline policies that are embedded in the specified IAM
          group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=ListGroupPolicies
  tags: Group Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionlistgrouppolicies-get-openapi.md
- name: AWS Identity and Access Management API List Groups
  x-api-slug: aws-identity-and-access-management-api
  description: Lists the IAM groups that have the specified path prefix.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=ListGroups
  tags: Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionlistgroups-get-openapi.md
- name: AWS Identity and Access Management API List Groups For User
  x-api-slug: aws-identity-and-access-management-api
  description: Lists the IAM groups that the specified IAM user belongs to.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=ListGroupsForUser
  tags: Groups For User
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionlistgroupsforuser-get-openapi.md
- name: AWS Identity and Access Management API List Instance Profiles
  x-api-slug: aws-identity-and-access-management-api
  description: Lists the instance profiles that have the specified path prefix.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=ListInstanceProfiles
  tags: Instance Profiles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionlistinstanceprofiles-get-openapi.md
- name: AWS Identity and Access Management API List Instance Profiles For Role
  x-api-slug: aws-identity-and-access-management-api
  description: Lists the instance profiles that have the specified associated IAM
    role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=ListInstanceProfilesForRole
  tags: Instance Profiles For Role
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionlistinstanceprofilesforrole-get-openapi.md
- name: AWS Identity and Access Management API List M F A Devices
  x-api-slug: aws-identity-and-access-management-api
  description: Lists the MFA devices for an IAM user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=ListMFADevices
  tags: MFA Devices
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionlistmfadevices-get-openapi.md
- name: AWS Identity and Access Management API List Open I D Connect Providers
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Lists information about the IAM OpenID Connect (OIDC) provider resource objects
          defined in the AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=ListOpenIDConnectProviders
  tags: OpenID Connect Providers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionlistopenidconnectproviders-get-openapi.md
- name: AWS Identity and Access Management API List Policies
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Lists all the managed policies that are available in your AWS account, including your
          own customer-defined managed policies and all AWS managed policies.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=ListPolicies
  tags: listPolicies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionlistpolicies-get-openapi.md
- name: AWS Identity and Access Management API List Policy Versions
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Lists information about the versions of the specified managed policy, including the
          version that is currently set as the policy's default version.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=ListPolicyVersions
  tags: Policy Versions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionlistpolicyversions-get-openapi.md
- name: AWS Identity and Access Management API List Role Policies
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Lists the names of the inline policies that are embedded in the specified IAM
          role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=ListRolePolicies
  tags: Role Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionlistrolepolicies-get-openapi.md
- name: AWS Identity and Access Management API List Roles
  x-api-slug: aws-identity-and-access-management-api
  description: Lists the IAM roles that have the specified path prefix.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=ListRoles
  tags: Roles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionlistroles-get-openapi.md
- name: AWS Identity and Access Management API List S A M L Providers
  x-api-slug: aws-identity-and-access-management-api
  description: Lists the SAML provider resource objects defined in IAM in the account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=ListSAMLProviders
  tags: SAML Providers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionlistsamlproviders-get-openapi.md
- name: AWS Identity and Access Management API List Server Certificates
  x-api-slug: aws-identity-and-access-management-api
  description: Lists the server certificates stored in IAM that have the specified
    path prefix.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=ListServerCertificates
  tags: Serve rCertificates
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionlistservercertificates-get-openapi.md
- name: AWS Identity and Access Management API List Service Specific Credentials
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Returns information about the service-specific credentials associated with the
          specified IAM user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=ListServiceSpecificCredentials
  tags: Service Specific Credentials
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionlistservicespecificcredentials-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionlistservicespecificcredentials-get-openapi.md
- name: AWS Identity and Access Management API List Signing Certificates
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Returns information about the signing certificates associated with the specified IAM
          user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=ListSigningCertificates
  tags: Signing Certificates
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionlistsigningcertificates-get-openapi.md
- name: AWS Identity and Access Management API List S S H Public Keys
  x-api-slug: aws-identity-and-access-management-api
  description: Returns information about the SSH public keys associated with the specified
    IAM user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=ListSSHPublicKeys
  tags: SSH Public Keys
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionlistsshpublickeys-get-openapi.md
- name: AWS Identity and Access Management API List User Policies
  x-api-slug: aws-identity-and-access-management-api
  description: Lists the names of the inline policies embedded in the specified IAM
    user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=ListUserPolicies
  tags: User Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionlistuserpolicies-get-openapi.md
- name: AWS Identity and Access Management API List Users
  x-api-slug: aws-identity-and-access-management-api
  description: Lists the IAM users that have the specified path prefix.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=ListUsers
  tags: Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionlistusers-get-openapi.md
- name: AWS Identity and Access Management API List Virtual M F A Devices
  x-api-slug: aws-identity-and-access-management-api
  description: Lists the virtual MFA devices defined in the AWS account by assignment
    status.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=ListVirtualMFADevices
  tags: Virtual MFA Devices
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionlistvirtualmfadevices-get-openapi.md
- name: AWS Identity and Access Management API Put Group Policy
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Adds or updates an inline policy document that is embedded in the specified IAM
          group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=PutGroupPolicy
  tags: Group Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionputgrouppolicy-get-openapi.md
- name: AWS Identity and Access Management API Put Role Policy
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Adds or updates an inline policy document that is embedded in the specified IAM
          role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=PutRolePolicy
  tags: Role Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionputrolepolicy-get-openapi.md
- name: AWS Identity and Access Management API Put User Policy
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Adds or updates an inline policy document that is embedded in the specified IAM
          user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=PutUserPolicy
  tags: Users Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionputuserpolicy-get-openapi.md
- name: AWS Identity and Access Management API Remove Client I D From Open I D Connect
    Provider
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Removes the specified client ID (also known as audience) from the list of client IDs
          registered for the specified IAM OpenID Connect (OIDC) provider resource object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=RemoveClientIDFromOpenIDConnectProvider
  tags: OpenID Connect Providers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionremoveclientidfromopenidconnectprovider-get-openapi.md
- name: AWS Identity and Access Management API Remove Role From Instance Profile
  x-api-slug: aws-identity-and-access-management-api
  description: Removes the specified IAM role from the specified EC2 instance profile.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=RemoveRoleFromInstanceProfile
  tags: Role From Instance Profiles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionremoverolefrominstanceprofile-get-openapi.md
- name: AWS Identity and Access Management API Remove User From Group
  x-api-slug: aws-identity-and-access-management-api
  description: Removes the specified user from the specified group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=RemoveUserFromGroup
  tags: User From Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionremoveuserfromgroup-get-openapi.md
- name: AWS Identity and Access Management API Reset Service Specific Credential
  x-api-slug: aws-identity-and-access-management-api
  description: Resets the password for a service-specific credential.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=ResetServiceSpecificCredential
  tags: Service Specific Credentials
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionresetservicespecificcredential-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionresetservicespecificcredential-get-openapi.md
- name: AWS Identity and Access Management API Resync M F A Device
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Synchronizes the specified MFA device with its IAM resource object on the AWS
          servers.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=ResyncMFADevice
  tags: MFA Devices
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionresyncmfadevice-get-openapi.md
- name: AWS Identity and Access Management API Set Default Policy Version
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Sets the specified version of the specified policy as the policy's default (operative)
          version.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=SetDefaultPolicyVersion
  tags: Default Policy Versions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionsetdefaultpolicyversion-get-openapi.md
- name: AWS Identity and Access Management API Simulate Custom Policy
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Simulate how a set of IAM policies and optionally a resource-based policy works with
          a list of API actions and AWS resources to determine the policies' effective permissions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=SimulateCustomPolicy
  tags: Custom Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionsimulatecustompolicy-get-openapi.md
- name: AWS Identity and Access Management API Simulate Principal Policy
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Simulate how a set of IAM policies attached to an IAM entity works with a list of
          API actions and AWS resources to determine the policies' effective permissions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=SimulatePrincipalPolicy
  tags: Principal Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionsimulateprincipalpolicy-get-openapi.md
- name: AWS Identity and Access Management API Update Access Key
  x-api-slug: aws-identity-and-access-management-api
  description: Changes the status of the specified access key from Active to Inactive,
    or vice versa.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=UpdateAccessKey
  tags: Access Keys
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionupdateaccesskey-get-openapi.md
- name: AWS Identity and Access Management API Update Account Password Policy
  x-api-slug: aws-identity-and-access-management-api
  description: Updates the password policy settings for the AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=UpdateAccountPasswordPolicy
  tags: Account Password Policy
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionupdateaccountpasswordpolicy-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionupdateaccountpasswordpolicy-get-openapi.md
- name: AWS Identity and Access Management API Update Assume Role Policy
  x-api-slug: aws-identity-and-access-management-api
  description: Updates the policy that grants an IAM entity permission to assume a
    role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=UpdateAssumeRolePolicy
  tags: Assume Role Policy
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionupdateassumerolepolicy-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionupdateassumerolepolicy-get-openapi.md
- name: AWS Identity and Access Management API Update Group
  x-api-slug: aws-identity-and-access-management-api
  description: Updates the name and/or the path of the specified IAM group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=UpdateGroup
  tags: Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionupdategroup-get-openapi.md
- name: AWS Identity and Access Management API Update Login Profile
  x-api-slug: aws-identity-and-access-management-api
  description: Changes the password for the specified IAM user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=UpdateLoginProfile
  tags: Login Profiles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionupdateloginprofile-get-openapi.md
- name: AWS Identity and Access Management API Update Open I D Connect Provider Thumbprint
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Replaces the existing list of server certificate thumbprints associated with an OpenID
          Connect (OIDC) provider resource object with a new list of thumbprints.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=UpdateOpenIDConnectProviderThumbprint
  tags: OpenID Connect Providers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionupdateopenidconnectproviderthumbprint-get-openapi.md
- name: AWS Identity and Access Management API Update S A M L Provider
  x-api-slug: aws-identity-and-access-management-api
  description: Updates the metadata document for an existing SAML provider resource
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=UpdateSAMLProvider
  tags: SAML Provider
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionupdatesamlprovider-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionupdatesamlprovider-get-openapi.md
- name: AWS Identity and Access Management API Update Server Certificate
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Updates the name and/or the path of the specified server certificate stored in
          IAM.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=UpdateServerCertificate
  tags: Server Certificates
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionupdateservercertificate-get-openapi.md
- name: AWS Identity and Access Management API Update Service Specific Credential
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Sets the status of a service-specific credential to Active or
            Inactive.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=UpdateServiceSpecificCredential
  tags: Service Specific Credentials
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionupdateservicespecificcredential-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionupdateservicespecificcredential-get-openapi.md
- name: AWS Identity and Access Management API Update Signing Certificate
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Changes the status of the specified user signing certificate from active to disabled,
          or vice versa.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=UpdateSigningCertificate
  tags: Signing Certificates
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionupdatesigningcertificate-get-openapi.md
- name: AWS Identity and Access Management API Update S S H Public Key
  x-api-slug: aws-identity-and-access-management-api
  description: Sets the status of an IAM user's SSH public key to active or inactive.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=UpdateSSHPublicKey
  tags: SSH Public Keys
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionupdatesshpublickey-get-openapi.md
- name: AWS Identity and Access Management API Update User
  x-api-slug: aws-identity-and-access-management-api
  description: Updates the name and/or the path of the specified IAM user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=UpdateUser
  tags: Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionupdateuser-get-openapi.md
- name: AWS Identity and Access Management API Upload Server Certificate
  x-api-slug: aws-identity-and-access-management-api
  description: Uploads a server certificate entity for the AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=UploadServerCertificate
  tags: Server Certificates
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionuploadservercertificate-get-openapi.md
- name: AWS Identity and Access Management API Upload Signing Certificate
  x-api-slug: aws-identity-and-access-management-api
  description: Uploads an X.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=UploadSigningCertificate
  tags: Signing Certificates
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionuploadsigningcertificate-get-openapi.md
- name: AWS Identity and Access Management API Upload S S H Public Key
  x-api-slug: aws-identity-and-access-management-api
  description: Uploads an SSH public key and associates it with the specified IAM
    user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=UploadSSHPublicKey
  tags: SSH Public Key
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionuploadsshpublickey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/actionuploadsshpublickey-get-openapi.md
- name: AWS Identity and Access Management API
  x-api-slug: aws-identity-and-access-management-api
  description: AWS Identity and Access Management (IAM) enables you to securely control
    access to AWS services and resources for your users. Using IAM, you can create
    and manage AWS users and groups, and use permissions to allow and deny their access
    to AWS resources.IAM is a feature of your AWS account offered at no additional
    charge. You will be charged only for use of other AWS services by your users.To
    get started using IAM, orif you have already registered with AWS, go to theAWS
    Management Consoleand get started with theseIAM Best Practices.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: AWS Identity and Access Management
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-identity-and-access-management/master/_listings/aws-identity-and-access-management/openapi.md
x-common:
- type: x-change-log
  url: http://developer.amazonwebservices.com/connect/kbcategory.jspa?categoryID=323
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/cli/latest/reference/sts/index.html
- type: x-documentation
  url: http://docs.aws.amazon.com/IAM/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/iam/faqs/
- type: x-forum
  url: https://forums.aws.amazon.com/forum.jspa?forumID=76
- type: x-getting-started
  url: https://aws.amazon.com/iam/getting-started/
- type: x-partners
  url: https://aws.amazon.com/iam/partners/
- type: x-tools
  url: http://aws.amazon.com/cli
- type: x-website
  url: https://aws.amazon.com/iam/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---