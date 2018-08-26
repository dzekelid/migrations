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
  /api/WalletMigration:
    post:
      summary: Add API Walletmigration
      description: Add api walletmigration.
      operationId: ApiWalletMigrationPost
      x-api-path-slug: apiwalletmigration-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: data
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Walletmigration
---