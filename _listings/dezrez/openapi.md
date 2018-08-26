---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 1
info:
  title: Dezrez.Rezi.Client.Api
  version: 1.0.0
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/credentials/deleteusernamepassword/{name}:
    delete:
      summary: Delete Security Credentials
      description: Delete security credentials.
      operationId: Credentials_DeleteUsernamePasswordByname
      x-api-path-slug: apicredentialsdeleteusernamepasswordname-delete
      parameters:
      - in: path
        name: name
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Security
      - Credentials
  /api/credentials/emailsync/usernamepassword:
    get:
      summary: Gets Email Sync Security Credentials
      description: Gets email sync security credentials.
      operationId: Credentials_EmailSyncUsernamePasswordBycredentialDataContract.usernameBycredentialDataContract.passw
      x-api-path-slug: apicredentialsemailsyncusernamepassword-get
      parameters:
      - in: query
        name: credentialDataContract.password
      - in: query
        name: credentialDataContract.username
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - S
      - Email
      - Sync
      - Security
      - Credentials
    post:
      summary: "Creates or Updates Email Sync Security Credentials\r\nThis also uses
        the credentials to do a quick check and see if they are working\r\nit will
        throw an internal server error if there is an issue with the connection\r\nbut
        this may be the server address (s"
      description: "Creates or updates email sync security credentials\r\nthis also
        uses the credentials to do a quick check and see if they are working\r\nit
        will throw an internal server error if there is an issue with the connection\r\nbut
        this may be the server address (s."
      operationId: Credentials_UpsertEmailSyncUsernamePasswordBycredentialDataContract
      x-api-path-slug: apicredentialsemailsyncusernamepassword-post
      parameters:
      - in: body
        name: credentialDataContract
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Creates
      - S
      - Email
      - Sync
      - Security
      - "Credentials\r\nThis"
      - Also
      - Uses
      - Credentials
      - To
      - Do
      - Quick
      - Check
      - See
      - If
      - They
      - Are
      - "Working\r\nIt"
      - Will
      - Throw
      - Internal
      - Server
      - Error
      - If
      - There
      - Is
      - Issue
      - "Connection\r\nBut"
      - This
      - May
      - Be
      - Server
      - Address
      - (s
  /api/credentials/upsertusernamepassword:
    post:
      summary: Creates or Updates Security Credentials
      description: Creates or updates security credentials.
      operationId: Credentials_UpsertUsernamePasswordBycredentialDataContract
      x-api-path-slug: apicredentialsupsertusernamepassword-post
      parameters:
      - in: body
        name: credentialDataContract
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Creates
      - S
      - Security
      - Credentials
---