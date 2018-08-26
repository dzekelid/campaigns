---
swagger: "2.0"
x-collection-name: AWS Pinpoint
x-complete: 1
info:
  title: AWS Pinpoint API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /apps/application-id/campaigns/:
    get:
      summary: Get Campaigns
      description: Campaigns are messaging initiatives that engage specific segments
        of end users. The information represented by this resource includes the segment
        that the campaign reaches out to, the message that it delivers, and the schedule
        on which it runs. You can use this resource to look up, create, update, or
        delete campaigns.
      operationId: campaigns
      x-api-path-slug: appsapplicationidcampaigns-get
      parameters:
      - in: header
        name: accept
        description: 'Specify the media type you will accept as a response:  application/json
          ??? A JSON response body'
        type: string
        format: string
      - in: query
        name: page-size
        description: The number of entries you want on each page in the response
        type: string
        format: string
      - in: query
        name: token
        description: An identifier used to retrieve the next page of results
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Campaign
---