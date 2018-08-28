---
swagger: "2.0"
x-collection-name: Heroku
x-complete: 0
info:
  title: Heroku Put Application Stack
  description: Migrate an app to a new stack.
  version: "1"
host: api.heroku.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /apps/{app}/stack:
    put:
      summary: Put Application Stack
      description: Migrate an app to a new stack.
      operationId: putAppsAppStack
      x-api-path-slug: appsappstack-put
      parameters:
      - in: query
        name: Accept
        description: Content type
      - in: header
        name: Accept
        description: Content type
      - in: query
        name: app
        description: The app name
      - in: path
        name: app
      responses:
        200:
          description: OK
      tags:
      - Put
      - Application
      - Stack
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