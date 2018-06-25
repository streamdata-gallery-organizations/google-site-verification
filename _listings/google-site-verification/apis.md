---
name: Google Site Verification
x-slug: google-site-verification
description: The Google Site Verification API lets you develop applications or services
  that automate the process of verifying that the authenticated user owns a domain
  or website. This is important, since some Google services can only be used by site
  owners.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-site-verification-500x362.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Google Site Verification
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-site-verification/master/_listings/google-site-verification/apis.md
specificationVersion: "0.14"
apis:
- name: Google Site Verification API Get Token
  x-api-slug: google-site-verification-api
  description: Get a verification token for placing on a website or domain.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-site-verification-500x362.png
  humanURL: https://developers.google.com/site-verification/
  baseURL: ://www.googleapis.com//siteVerification/v1//token
  tags: Token
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-site-verification/master/_listings/google-site-verification/token-post-openapi.md
- name: Google Site Verification API Get Verified Websites
  x-api-slug: google-site-verification-api
  description: Get the list of your verified websites and domains.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-site-verification-500x362.png
  humanURL: https://developers.google.com/site-verification/
  baseURL: ://www.googleapis.com//siteVerification/v1//webResource
  tags: Website
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-site-verification/master/_listings/google-site-verification/webresource-get-openapi.md
- name: Google Site Verification API Verify Website
  x-api-slug: google-site-verification-api
  description: Attempt verification of a website or domain.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-site-verification-500x362.png
  humanURL: https://developers.google.com/site-verification/
  baseURL: ://www.googleapis.com//siteVerification/v1//webResource
  tags: Website
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-site-verification/master/_listings/google-site-verification/webresource-post-openapi.md
- name: Google Site Verification API Relinquish Ownership Of Website
  x-api-slug: google-site-verification-api
  description: Relinquish ownership of a website or domain.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-site-verification-500x362.png
  humanURL: https://developers.google.com/site-verification/
  baseURL: ://www.googleapis.com//siteVerification/v1//webResource/{id}
  tags: Website
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-site-verification/master/_listings/google-site-verification/webresourceid-delete-openapi.md
- name: Google Site Verification API Get Current Data for Website
  x-api-slug: google-site-verification-api
  description: Get the most current data for a website or domain.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-site-verification-500x362.png
  humanURL: https://developers.google.com/site-verification/
  baseURL: ://www.googleapis.com//siteVerification/v1//webResource/{id}
  tags: Website
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-site-verification/master/_listings/google-site-verification/webresourceid-get-openapi.md
- name: Google Site Verification API Update List of Owners for Website
  x-api-slug: google-site-verification-api
  description: Modify the list of owners for your website or domain. This method supports
    patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-site-verification-500x362.png
  humanURL: https://developers.google.com/site-verification/
  baseURL: ://www.googleapis.com//siteVerification/v1//webResource/{id}
  tags: Website
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-site-verification/master/_listings/google-site-verification/webresourceid-patch-openapi.md
- name: Google Site Verification API Update List of Owners for Website
  x-api-slug: google-site-verification-api
  description: Modify the list of owners for your website or domain.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-site-verification-500x362.png
  humanURL: https://developers.google.com/site-verification/
  baseURL: ://www.googleapis.com//siteVerification/v1//webResource/{id}
  tags: Website
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-site-verification/master/_listings/google-site-verification/webresourceid-put-openapi.md
- name: Google Site Verification API
  x-api-slug: google-site-verification-api
  description: The Google Site Verification API lets you develop applications or services
    that automate the process of verifying that the authenticated user owns a domain
    or website. This is important, since some Google services can only be used by
    site owners.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-site-verification-500x362.png
  humanURL: https://developers.google.com/site-verification/
  baseURL: ://www.googleapis.com//siteVerification/v1
  tags: Google Site Verification
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-site-verification/master/_listings/google-site-verification/openapi.md
x-common:
- type: x-code
  url: https://developers.google.com/site-verification/libraries
- type: x-documentation
  url: https://developers.google.com/site-verification/v1/
- type: x-website
  url: https://developers.google.com/site-verification/
- type: x-getting-started
  url: https://developers.google.com/site-verification/v1/getting_started
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---