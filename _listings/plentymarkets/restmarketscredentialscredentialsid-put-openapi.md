---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets Update a credential
  description: Update a credential with the given data and ID.
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/markets/credentials:
    post:
      summary: Create a credential
      description: Create a new credential with the given data.
      operationId: postRestMarketsCredentials
      x-api-path-slug: restmarketscredentials-post
      parameters:
      - in: body
        name: /rest/markets/credentials
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Credential
  /rest/markets/credentials/{credentialsId}:
    delete:
      summary: Delete a credential
      description: Deletes a credential by given ID.
      operationId: deleteRestMarketsCredentialsCredentials
      x-api-path-slug: restmarketscredentialscredentialsid-delete
      parameters:
      - in: path
        name: credentialsId
      - in: query
        name: id
        description: The ID of the credentials to be deleted
      responses:
        200:
          description: OK
      tags:
      - Credential
    get:
      summary: Get a credential
      description: Get a credential.
      operationId: getRestMarketsCredentialsCredentials
      x-api-path-slug: restmarketscredentialscredentialsid-get
      parameters:
      - in: path
        name: credentialsId
      - in: query
        name: id
        description: The ID of the credentials to be found
      responses:
        200:
          description: OK
      tags:
      - Credential
    put:
      summary: Update a credential
      description: Update a credential with the given data and ID.
      operationId: putRestMarketsCredentialsCredentials
      x-api-path-slug: restmarketscredentialscredentialsid-put
      parameters:
      - in: body
        name: /rest/markets/credentials/{credentialsId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: credentialsId
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