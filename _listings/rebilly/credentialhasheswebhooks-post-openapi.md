---
swagger: "2.0"
x-collection-name: Rebilly
x-complete: 0
info:
  title: Rebilly Create a webhook credential
  description: Create a webhook credential
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
    put:
      summary: Create or update a credential with predefined ID
      description: Create or update a credential with predefined identifier string
      operationId: credentials.id.put
      x-api-path-slug: credentialsid-put
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
      - Update
      - Credential
      - Predefined
      - ID
  /credential-hashes/emails:
    post:
      summary: Create an email credential
      description: Create an email credential
      operationId: create-an-email-credential
      x-api-path-slug: credentialhashesemails-post
      parameters:
      - in: body
        name: body
        description: Email credential resource
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Email
      - Credential
  /credential-hashes/emails/{hash}:
    get:
      summary: Retrieve an email credential
      description: Retrieve an email credential with specified token identifier string
      operationId: retrieve-an-email-credential-with-specified-token-identifier-string
      x-api-path-slug: credentialhashesemailshash-get
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Email
      - Credential
  /credential-hashes/webhooks:
    post:
      summary: Create a webhook credential
      description: Create a webhook credential
      operationId: create-a-webhook-credential
      x-api-path-slug: credentialhasheswebhooks-post
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
      - Webhook
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