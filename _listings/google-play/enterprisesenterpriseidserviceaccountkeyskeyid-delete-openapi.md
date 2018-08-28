---
swagger: "2.0"
x-collection-name: Google Play
x-complete: 0
info:
  title: Google Play Remove and Invalidates Credentials
  version: 1.0.0
  description: Removes and invalidates the specified credentials for the service account
    associated with this enterprise. The calling service account must have been retrieved
    by calling Enterprises.GetServiceAccount and must have been set as the enterprise
    service account by calling Enterprises.SetAccount.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /enterprises/{enterpriseId}/serviceAccountKeys:
    get:
      summary: Return Active Credentials
      description: Lists all active credentials for the service account associated
        with this enterprise. Only the ID and key type are returned. The calling service
        account must have been retrieved by calling Enterprises.GetServiceAccount
        and must have been set as the enterprise service account by calling Enterprises.SetAccount.
      operationId: androidenterprise.serviceaccountkeys.list
      x-api-path-slug: enterprisesenterpriseidserviceaccountkeys-get
      parameters:
      - in: path
        name: enterpriseId
        description: The ID of the enterprise
      responses:
        200:
          description: OK
      tags:
      - Credential
    post:
      summary: Generate New Credentials
      description: |-
        Generates new credentials for the service account associated with this enterprise. The calling service account must have been retrieved by calling Enterprises.GetServiceAccount and must have been set as the enterprise service account by calling Enterprises.SetAccount.

        Only the type of the key should be populated in the resource to be inserted.
      operationId: androidenterprise.serviceaccountkeys.insert
      x-api-path-slug: enterprisesenterpriseidserviceaccountkeys-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: enterpriseId
        description: The ID of the enterprise
      responses:
        200:
          description: OK
      tags:
      - Credential
  /enterprises/{enterpriseId}/serviceAccountKeys/{keyId}:
    delete:
      summary: Remove and Invalidates Credentials
      description: Removes and invalidates the specified credentials for the service
        account associated with this enterprise. The calling service account must
        have been retrieved by calling Enterprises.GetServiceAccount and must have
        been set as the enterprise service account by calling Enterprises.SetAccount.
      operationId: androidenterprise.serviceaccountkeys.delete
      x-api-path-slug: enterprisesenterpriseidserviceaccountkeyskeyid-delete
      parameters:
      - in: path
        name: enterpriseId
        description: The ID of the enterprise
      - in: path
        name: keyId
        description: The ID of the key
      responses:
        200:
          description: OK
      tags:
      - Credential
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