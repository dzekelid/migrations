swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 1
info:
  title: plentymarkets REST-API
  description: the-plentymarkets-rest-api-expands-the-functionality-of-the-plentymarkets-cms-and-allows-access-to-resources-i-e--data-records-via-unique-uri-paths
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
  /rest/feedbacks/migrate:
    post:
      summary: Migrate legacy feedbacks
      description: Migrate legacy feedbacks.
      operationId: postRestFeedbacksMigrate
      x-api-path-slug: restfeedbacksmigrate-post
      responses:
        200:
          description: OK
      tags:
      - Migrate
      - Legacy
      - Feedbacks