---
swagger: "2.0"
x-collection-name: Lykke
x-complete: 0
info:
  title: Lykke Get API Swiftcredentials Asset
  version: 1.0.0
  description: Get api swiftcredentials asset.
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/SwiftCredentials:
    get:
      summary: Get API Swiftcredentials
      description: Get api swiftcredentials.
      operationId: ApiSwiftCredentialsGet
      x-api-path-slug: apiswiftcredentials-get
      responses:
        200:
          description: OK
      tags:
      - Swiftcredentials
  /api/SwiftCredentials/{assetId}:
    get:
      summary: Get API Swiftcredentials Asset
      description: Get api swiftcredentials asset.
      operationId: ApiSwiftCredentialsByAssetIdGet
      x-api-path-slug: apiswiftcredentialsassetid-get
      parameters:
      - in: path
        name: assetId
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - Swiftcredentials
      - Asset
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