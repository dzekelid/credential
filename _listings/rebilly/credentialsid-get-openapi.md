---
swagger: "2.0"
x-collection-name: Rebilly
x-complete: 0
info:
  title: Rebilly Retrieve a credential
  description: Retrieve a credential with specified identifier string
  termsOfService: https://www.rebilly.com/terms/
  contact:
    name: Rebilly API Support
    url: https://www.rebilly.com/contact/
    email: integrations@rebilly.com
  version: "2.1"
host: api.rebilly.com
basePath: /v2.1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /credentials:
    post:
      summary: Create a credential
      description: Create a credential
      operationId: credentials.post
      x-api-path-slug: credentials-post
      parameters:
      - in: body
        name: body
        description: Credential resource
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Credential
  /credentials/{id}:
    delete:
      summary: Delete a credential
      description: Delete a credential with predefined identifier string
      operationId: credentials.id.delete
      x-api-path-slug: credentialsid-delete
      responses:
        200:
          description: OK
      tags:
      - Credential
    get:
      summary: Retrieve a credential
      description: Retrieve a credential with specified identifier string
      operationId: credentials.id.get
      x-api-path-slug: credentialsid-get
      responses:
        200:
          description: OK
      tags:
      - Retrieve
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