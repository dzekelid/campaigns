---
name: HHS Media Services
x-slug: hhs-media-services
description: Use this API platform to create sites with text and multimedia content
  for syndication. CDC, FDA, HHS, and NIH have built syndication sites using this
  platform, which is available in Java and .NET.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/hhs-media-services.png
x-kinRank: "7"
x-alexaRank: "0"
tags: Campaigns
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/campaigns/master/_listings/hhs-media-services/apis.md
specificationVersion: "0.14"
apis:
- name: HHS Media Services Get Campaigns
  x-api-slug: hhs-media-services
  description: Returns the list of Campaigns.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/hhs-media-services.png
  humanURL: https://api.digitalmedia.hhs.gov/
  baseURL: https://api.digitalmedia.hhs.gov//api/v2//resources/campaigns.json
  tags: Resources,Campaigns
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/campaigns/master/_listings/hhs-media-services/resourcescampaigns-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/campaigns/master/_listings/hhs-media-services/resourcescampaigns-json-get-openapi.md
- name: HHS Media Services Get Campaign by ID
  x-api-slug: hhs-media-services
  description: Returns the Campaign identified by the 'id'.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/hhs-media-services.png
  humanURL: https://api.digitalmedia.hhs.gov/
  baseURL: https://api.digitalmedia.hhs.gov//api/v2//resources/campaigns/{id}.json
  tags: Resources,Campaigns,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/campaigns/master/_listings/hhs-media-services/resourcescampaignsid-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/campaigns/master/_listings/hhs-media-services/resourcescampaignsid-json-get-openapi.md
- name: HHS Media Services Get MediaItems by Campaign ID
  x-api-slug: hhs-media-services
  description: Returns the list of MediaItems for the Campaign identified by the 'id'.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/hhs-media-services.png
  humanURL: https://api.digitalmedia.hhs.gov/
  baseURL: https://api.digitalmedia.hhs.gov//api/v2//resources/campaigns/{id}/media.json
  tags: Resources,Campaigns,Id,Media
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/campaigns/master/_listings/hhs-media-services/resourcescampaignsidmedia-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/campaigns/master/_listings/hhs-media-services/resourcescampaignsidmedia-json-get-openapi.md
- name: HHS Media Services Get MediaItems for Campaign
  x-api-slug: hhs-media-services
  description: Renders the list of MediaItems associated with the Campaign identified
    by the 'id'.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/hhs-media-services.png
  humanURL: https://api.digitalmedia.hhs.gov/
  baseURL: https://api.digitalmedia.hhs.gov//api/v2//resources/campaigns/{id}/syndicate.json
  tags: Resources,Campaigns,Id,Syndicate
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/campaigns/master/_listings/hhs-media-services/resourcescampaignsidsyndicate-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/campaigns/master/_listings/hhs-media-services/resourcescampaignsidsyndicate-json-get-openapi.md
- name: HHS Media Services
  x-api-slug: hhs-media-services
  description: Use this API platform to create sites with text and multimedia content
    for syndication. CDC, FDA, HHS, and NIH have built syndication sites using this
    platform, which is available in Java and .NET.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/hhs-media-services.png
  humanURL: https://api.digitalmedia.hhs.gov/
  baseURL: https://api.digitalmedia.hhs.gov//api/v2
  tags: Campaigns
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/campaigns/master/_listings/hhs-media-services/openapi.md
x-common:
- type: x-website
  url: https://api.digitalmedia.hhs.gov/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---