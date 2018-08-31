---
name: Knoema
x-slug: knoema
description: Knoema is the free to use public and open data platform for users with
  interests in statistics and data analysis, visual storytelling and making infographics
  and data-driven presentations
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/knoema-logo.jpg
x-kinRank: "8"
x-alexaRank: "38551"
tags: Knoema
created: "2018-08-30"
modified: "2018-08-30"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/knoema/master/_listings/knoema/apis.md
specificationVersion: "0.14"
apis:
- name: Knoema - List of datasets
  x-api-slug: metadataset-get
  description: Returns the list of datasets
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/knoema-logo.jpg
  humanURL: https://knoema.com
  baseURL: http://knoema.com//api/1.0
  tags: Data, Finance, Finance, Technology, SaaS, Enterprise, Market Data, Sign In
    With Facebook, Sign In With Google, Sign In With LinkedIn, REST, JSON, Free Tier,
    Data Provider, API Provider, Profiles, General Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/knoema/master/_listings/knoema/metadataset-get-openapi.md
- name: Knoema - Dataset details
  x-api-slug: metadatasetdataset-id-get
  description: Lists out details of a particular dataset.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/knoema-logo.jpg
  humanURL: https://knoema.com
  baseURL: http://knoema.com//api/1.0
  tags: Data, Finance, Finance, Technology, SaaS, Enterprise, Market Data, Sign In
    With Facebook, Sign In With Google, Sign In With LinkedIn, REST, JSON, Free Tier,
    Data Provider, API Provider, Profiles, General Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/knoema/master/_listings/knoema/metadatasetdataset-id-get-openapi.md
- name: Knoema - Dimension
  x-api-slug: metadatasetdatasetiddimensiondimensionid-get
  description: Lists out the given dataset's dimension details.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/knoema-logo.jpg
  humanURL: https://knoema.com
  baseURL: http://knoema.com//api/1.0
  tags: Data, Finance, Finance, Technology, SaaS, Enterprise, Market Data, Sign In
    With Facebook, Sign In With Google, Sign In With LinkedIn, REST, JSON, Free Tier,
    Data Provider, API Provider, Profiles, General Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/knoema/master/_listings/knoema/metadatasetdatasetiddimensiondimensionid-get-openapi.md
- name: Knoema - Dimension Group
  x-api-slug: metagroupgroupkey-get
  description: 'This endpoint used to list/add/edit/delete groups in dimensions. The
    functionality of endpoint depends on HTTP method: GET, POST, PUT or DELETE.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/knoema-logo.jpg
  humanURL: https://knoema.com
  baseURL: http://knoema.com//api/1.0
  tags: Data, Finance, Finance, Technology, SaaS, Enterprise, Market Data, Sign In
    With Facebook, Sign In With Google, Sign In With LinkedIn, REST, JSON, Free Tier,
    Data Provider, API Provider, Profiles, General Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/knoema/master/_listings/knoema/metagroupgroupkey-get-openapi.md
- name: Knoema - List of tags
  x-api-slug: frontendtags-get
  description: Lists out all the public tags present in the system
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/knoema-logo.jpg
  humanURL: https://knoema.com
  baseURL: http://knoema.com//api/1.0
  tags: Data, Finance, Finance, Technology, SaaS, Enterprise, Market Data, Sign In
    With Facebook, Sign In With Google, Sign In With LinkedIn, REST, JSON, Free Tier,
    Data Provider, API Provider, Profiles, General Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/knoema/master/_listings/knoema/frontendtags-get-openapi.md
- name: Knoema - Get timeseries list
  x-api-slug: datadatasetdataset-id-get
  description: For the given dataset, this endpoint returns time series list for all
    the available frequencies with the combination of all the dimension members.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/knoema-logo.jpg
  humanURL: https://knoema.com
  baseURL: http://knoema.com//api/1.0
  tags: Data, Finance, Finance, Technology, SaaS, Enterprise, Market Data, Sign In
    With Facebook, Sign In With Google, Sign In With LinkedIn, REST, JSON, Free Tier,
    Data Provider, API Provider, Profiles, General Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/knoema/master/_listings/knoema/datadatasetdataset-id-get-openapi.md
- name: Knoema - Get data
  x-api-slug: dataget-get
  description: This endpoint returns observation data for the given filter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/knoema-logo.jpg
  humanURL: https://knoema.com
  baseURL: http://knoema.com//api/1.0
  tags: Data, Finance, Finance, Technology, SaaS, Enterprise, Market Data, Sign In
    With Facebook, Sign In With Google, Sign In With LinkedIn, REST, JSON, Free Tier,
    Data Provider, API Provider, Profiles, General Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/knoema/master/_listings/knoema/dataget-get-openapi.md
- name: Knoema - Search by keyword
  x-api-slug: search-get
  description: This namespace provides search details for data accessible by that
    user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/knoema-logo.jpg
  humanURL: https://knoema.com
  baseURL: http://knoema.com//api/1.0
  tags: Data, Finance, Finance, Technology, SaaS, Enterprise, Market Data, Sign In
    With Facebook, Sign In With Google, Sign In With LinkedIn, REST, JSON, Free Tier,
    Data Provider, API Provider, Profiles, General Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/knoema/master/_listings/knoema/search-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://kentico.cloud.api.gallery.streamdata.io
- type: x-api-stack
  url: http://knoema.stack.network
- type: x-authentication
  url: https://knoema.com/dev/apps/authentication
- type: x-blog
  url: http://blog.knoema.com/
- type: x-blog-rss
  url: http://blog.knoema.com/feeds/posts/default?alt=rss
- type: x-crunchbase
  url: https://crunchbase.com/organization/knoema
- type: x-developer
  url: http://knoema.com/dev
- type: x-documentation
  url: https://knoema.com/dev/docs
- type: x-email
  url: jobs@knoema.com
- type: x-email
  url: veskin@knoema.com
- type: x-email
  url: jkasputys@knoema.com
- type: x-email
  url: vb@knoema.com
- type: x-email
  url: sales@knoema.com
- type: x-email
  url: info@knoema.com
- type: x-email
  url: support@knoema.com
- type: x-getting-started
  url: https://knoema.com/signup
- type: x-getting-started
  url: http://feedback.knoema.com/
- type: x-github
  url: https://github.com/knoema
- type: x-selfservice-registration
  url: https://knoema.com/sys/login?returnUrl=%2Fdev%2Fdocs%2Fmeta%2Fdatasets
- type: x-terms-of-service
  url: https://knoema.com/legal/termsofuse
- type: x-twitter
  url: https://twitter.com/knoema
- type: x-website
  url: https://knoema.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---