---
swagger: "2.0"
x-collection-name: Lykke
x-complete: 0
info:
  title: Lykke Add API Walletmigration
  version: 1.0.0
  description: Add api walletmigration.
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