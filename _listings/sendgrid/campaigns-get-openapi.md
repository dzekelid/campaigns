---
swagger: "2.0"
x-collection-name: SendGrid
x-complete: 0
info:
  title: SendGrid Get Campaigns
  description: |-
    **This endpoint allows you to retrieve a list of all of your campaigns.**

    Returns campaigns in reverse order they were created (newest first).

    Returns an empty array if no campaigns exist.

    For more information:

    * [User Guide > Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html)
  version: 1.0.0
host: api.sendgrid.com
basePath: /v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /campaigns:
    get:
      summary: Get Campaigns
      description: |-
        **This endpoint allows you to retrieve a list of all of your campaigns.**

        Returns campaigns in reverse order they were created (newest first).

        Returns an empty array if no campaigns exist.

        For more information:

        * [User Guide > Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html)
      operationId: GET_campaigns
      x-api-path-slug: campaigns-get
      parameters:
      - in: query
        name: limit
        description: The number of results you would like to receive at a time
      - in: query
        name: offset
        description: The index of the first campaign to return, where 0 is the first
          campaign
      responses:
        200:
          description: OK
      tags:
      - Email
      - Campaigns
x-streamrank:
  polling_total_time_average: "0"
  polling_size_download_average: "0"
  streaming_total_time_average: "0"
  streaming_size_download_average: "0"
  change_yes: "0"
  change_no: "0"
  time_percentage: "0"
  size_percentage: "0"
  change_percentage: "200"
  last_run: ~
  days_run: "0"
  minute_run: "0"
---