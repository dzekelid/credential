---
name: Google Play
x-slug: google-play
description: 'The Google Play Developer API allows you to perform a number of publishing
  and app-management tasks. It includes two components: The Subscriptions and In-App
  Purchases API lets you manage in-app purchases and subscriptions. The Publishing
  API lets you upload and publish apps, and perform other publishing-related tasks.'
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-play.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Credential
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/credential/master/_listings/google-play/apis.md
specificationVersion: "0.14"
apis:
- name: Google Play - Return Active Credentials
  x-api-slug: enterprisesenterpriseidserviceaccountkeys-get
  description: Lists all active credentials for the service account associated with
    this enterprise. Only the ID and key type are returned. The calling service account
    must have been retrieved by calling Enterprises.GetServiceAccount and must have
    been set as the enterprise service account by calling Enterprises.SetAccount.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-play.png
  humanURL: https://play.google.com/store
  baseURL: https:///
  tags: Google APIs, Android, Mobile, Gaming, Games, Movies, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/credential/master/_listings/google-play/enterprisesenterpriseidserviceaccountkeys-get-openapi.md
- name: Google Play - Generate New Credentials
  x-api-slug: enterprisesenterpriseidserviceaccountkeys-post
  description: |-
    Generates new credentials for the service account associated with this enterprise. The calling service account must have been retrieved by calling Enterprises.GetServiceAccount and must have been set as the enterprise service account by calling Enterprises.SetAccount.

    Only the type of the key should be populated in the resource to be inserted.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-play.png
  humanURL: https://play.google.com/store
  baseURL: https:///
  tags: Google APIs, Android, Mobile, Gaming, Games, Movies, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/credential/master/_listings/google-play/enterprisesenterpriseidserviceaccountkeys-post-openapi.md
- name: Google Play - Remove and Invalidates Credentials
  x-api-slug: enterprisesenterpriseidserviceaccountkeyskeyid-delete
  description: Removes and invalidates the specified credentials for the service account
    associated with this enterprise. The calling service account must have been retrieved
    by calling Enterprises.GetServiceAccount and must have been set as the enterprise
    service account by calling Enterprises.SetAccount.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-play.png
  humanURL: https://play.google.com/store
  baseURL: https:///
  tags: Google APIs, Android, Mobile, Gaming, Games, Movies, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/credential/master/_listings/google-play/enterprisesenterpriseidserviceaccountkeyskeyid-delete-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.people.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.play.stack.network
- type: x-blog
  url: https://blog.google/products/google-play/
- type: x-blog-rss
  url: https://blog.google/products/google-play/rss
- type: x-developer
  url: https://developers.google.com/android-publisher/
- type: x-facebook
  url: https://www.facebook.com/GooglePlay
- type: x-getting-started
  url: https://developers.google.com/android-publisher/getting_started
- type: x-twitter
  url: https://twitter.com/GooglePlay
- type: x-website
  url: https://play.google.com/store
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---