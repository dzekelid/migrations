---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Reports that a data migration has been shedueled - used by workflow
  version: 1.0.0
  description: Reports that a data migration has been shedueled - used by workflow.
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/coreplatformstate/reportMigration:
    post:
      summary: Reports that a data migration has been shedueled.
      description: Reports that a data migration has been shedueled..
      operationId: CorePlatformState_ReportMigrationStateBymigrationState
      x-api-path-slug: apicoreplatformstatereportmigration-post
      parameters:
      - in: body
        name: migrationState
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Reports
      - That
      - Data
      - Migration
      - Has
      - Been
      - Shedueled
  /api/coreplatformstate/reportMigration/{migrationId}:
    post:
      summary: Reports that a data migration has been shedueled - used by workflow
      description: Reports that a data migration has been shedueled - used by workflow.
      operationId: CorePlatformState_ReportMigrationStateBymigrationId
      x-api-path-slug: apicoreplatformstatereportmigrationmigrationid-post
      parameters:
      - in: path
        name: migrationId
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Reports
      - That
      - Data
      - Migration
      - Has
      - Been
      - Shedueled
      - '-'
      - Used
      - By
      - Workflow
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