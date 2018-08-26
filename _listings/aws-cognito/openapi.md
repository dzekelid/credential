---
swagger: "2.0"
x-collection-name: AWS Cognito
x-complete: 1
info:
  title: AWS Cognito Merged API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=GetCredentialsForIdentity:
    get:
      summary: Get Credentials For Identity
      description: Returns credentials for the provided identity ID.
      operationId: getCredentialsForIdentity
      x-api-path-slug: actiongetcredentialsforidentity-get
      parameters:
      - in: query
        name: CustomRoleArn
        description: The Amazon Resource Name (ARN) of the role to be assumed when
          multiple roles were         received in the token from the identity provider
        type: string
      - in: query
        name: IdentityId
        description: A unique identifier in the format REGION:GUID
        type: string
      - in: query
        name: Logins
        description: A set of optional name-value pairs that map provider names to
          provider         tokens
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identities
---