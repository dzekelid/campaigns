swagger: "2.0"
x-collection-name: Constant Contact
x-complete: 1
info:
  title: ConstantContact
  description: constant-contact-inc-is-an-online-marketing-company-offering-email-marketing-social-media-marketing-online-survey-and-event-marketing-tools-primarily-to-small-businesses-nonprofit-organizations-and-membership-associations-
  termsOfService: http://www.constantcontact.com/uidocs/CCSiteOwnerAgreement.jsp
  version: 1.0.0
host: api.constantcontact.com
basePath: /v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{username}/campaigns:
    get:
      summary: List Campaigns
      description: List Campaigns
      operationId: list-campaigns
      x-api-path-slug: usernamecampaigns-get
      parameters:
      - in: query
        name: refresh
        description: To initiate re-calculation of campaign results, you must use
          refresh= true
      - in: path
        name: username
      responses:
        200:
          description: OK
      tags:
      - List
      - Campaigns