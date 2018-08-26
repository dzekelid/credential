---
swagger: "2.0"
x-collection-name: Lykke
x-complete: 1
info:
  title: Wallet_Api
  version: 1.0.0
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
---