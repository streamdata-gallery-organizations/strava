---
name: Strava
x-slug: strava
description: Strava is software as a service used to track cycling, running, and swimming
  activity via GPS.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28739-strava.jpg
x-kinRank: "7"
x-alexaRank: "887"
tags: Strava
created: "2018-08-31"
modified: "2018-08-31"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/strava/master/_listings/strava/apis.md
specificationVersion: "0.14"
apis:
- name: Strava API v3 - Get Athlete Stats
  x-api-slug: athletesidstats-get
  description: Returns the activity stats of an athlete.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28739-strava.jpg
  humanURL: https://developers.strava.com
  baseURL: https://www.strava.com//api/v3
  tags: Mobile, Technology, internet, Sports, Athletes, Relative Data, Service API,
    New, Webhook Implementations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/strava/master/_listings/strava/athletesidstats-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/strava/master/_listings/strava/athletesidstats-get-openapi.md
- name: Strava API v3 - Get Authenticated Athlete
  x-api-slug: athlete-get
  description: Returns the currently authenticated athlete.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28739-strava.jpg
  humanURL: https://developers.strava.com
  baseURL: https://www.strava.com//api/v3
  tags: Mobile, Technology, internet, Sports, Athletes, Relative Data, Service API,
    New, Webhook Implementations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/strava/master/_listings/strava/athlete-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/strava/master/_listings/strava/athlete-get-openapi.md
- name: Strava API v3 - Update Athlete
  x-api-slug: athlete-put
  description: Update the currently authenticated athlete.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28739-strava.jpg
  humanURL: https://developers.strava.com
  baseURL: https://www.strava.com//api/v3
  tags: Mobile, Technology, internet, Sports, Athletes, Relative Data, Service API,
    New, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/strava/master/_listings/strava/athlete-put-openapi.md
- name: Strava API v3 - Get Zones
  x-api-slug: athletezones-get
  description: Returns the the authenticated athlete's heart rate and power zones.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28739-strava.jpg
  humanURL: https://developers.strava.com
  baseURL: https://www.strava.com//api/v3
  tags: Mobile, Technology, internet, Sports, Athletes, Relative Data, Service API,
    New, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/strava/master/_listings/strava/athletezones-get-openapi.md
- name: Strava API v3 - Get Segment
  x-api-slug: segmentsid-get
  description: Returns the specified segment.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28739-strava.jpg
  humanURL: https://developers.strava.com
  baseURL: https://www.strava.com//api/v3
  tags: Mobile, Technology, internet, Sports, Athletes, Relative Data, Service API,
    New, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/strava/master/_listings/strava/segmentsid-get-openapi.md
- name: Strava API v3 - List Starred Segments
  x-api-slug: segmentsstarred-get
  description: List of the authenticated athlete's starred segments.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28739-strava.jpg
  humanURL: https://developers.strava.com
  baseURL: https://www.strava.com//api/v3
  tags: Mobile, Technology, internet, Sports, Athletes, Relative Data, Service API,
    New, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/strava/master/_listings/strava/segmentsstarred-get-openapi.md
- name: Strava API v3 - Star Segment
  x-api-slug: segmentsidstarred-put
  description: Stars/Unstars the given segment for the authenticated athlete.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28739-strava.jpg
  humanURL: https://developers.strava.com
  baseURL: https://www.strava.com//api/v3
  tags: Mobile, Technology, internet, Sports, Athletes, Relative Data, Service API,
    New, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/strava/master/_listings/strava/segmentsidstarred-put-openapi.md
- name: Strava API v3 - Get Segment Leaderboard
  x-api-slug: segmentsidleaderboard-get
  description: Returns the specified segment leaderboard.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28739-strava.jpg
  humanURL: https://developers.strava.com
  baseURL: https://www.strava.com//api/v3
  tags: Mobile, Technology, internet, Sports, Athletes, Relative Data, Service API,
    New, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/strava/master/_listings/strava/segmentsidleaderboard-get-openapi.md
- name: Strava API v3 - List Segment Efforts
  x-api-slug: segmentsidall-efforts-get
  description: Returns a set of the authenticated athlete's segment efforts for a
    given segment.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28739-strava.jpg
  humanURL: https://developers.strava.com
  baseURL: https://www.strava.com//api/v3
  tags: Mobile, Technology, internet, Sports, Athletes, Relative Data, Service API,
    New, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/strava/master/_listings/strava/segmentsidall-efforts-get-openapi.md
- name: Strava API v3 - Explore segments
  x-api-slug: segmentsexplore-get
  description: Returns the top 10 segments matching a specified query.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28739-strava.jpg
  humanURL: https://developers.strava.com
  baseURL: https://www.strava.com//api/v3
  tags: Mobile, Technology, internet, Sports, Athletes, Relative Data, Service API,
    New, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/strava/master/_listings/strava/segmentsexplore-get-openapi.md
- name: Strava API v3 - Get Segment Effort
  x-api-slug: segment-effortsid-get
  description: Returns a segment effort from an activity that is owned by the authenticated
    athlete.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28739-strava.jpg
  humanURL: https://developers.strava.com
  baseURL: https://www.strava.com//api/v3
  tags: Mobile, Technology, internet, Sports, Athletes, Relative Data, Service API,
    New, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/strava/master/_listings/strava/segment-effortsid-get-openapi.md
- name: Strava API v3 - Get Running Race
  x-api-slug: running-racesid-get
  description: Returns a running race for a given identifier.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28739-strava.jpg
  humanURL: https://developers.strava.com
  baseURL: https://www.strava.com//api/v3
  tags: Mobile, Technology, internet, Sports, Athletes, Relative Data, Service API,
    New, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/strava/master/_listings/strava/running-racesid-get-openapi.md
- name: Strava API v3 - List Running Races
  x-api-slug: running-races-get
  description: Returns a list running races based on a set of search criteria.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28739-strava.jpg
  humanURL: https://developers.strava.com
  baseURL: https://www.strava.com//api/v3
  tags: Mobile, Technology, internet, Sports, Athletes, Relative Data, Service API,
    New, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/strava/master/_listings/strava/running-races-get-openapi.md
- name: Strava API v3 - Create an Activity
  x-api-slug: activities-post
  description: Creates a manual activity for an athlete. Requires write permissions,
    as requested during the authorization process.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28739-strava.jpg
  humanURL: https://developers.strava.com
  baseURL: https://www.strava.com//api/v3
  tags: Mobile, Technology, internet, Sports, Athletes, Relative Data, Service API,
    New, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/strava/master/_listings/strava/activities-post-openapi.md
- name: Strava API v3 - Get Activity
  x-api-slug: activitiesid-get
  description: Returns the given activity that is owned by the authenticated athlete.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28739-strava.jpg
  humanURL: https://developers.strava.com
  baseURL: https://www.strava.com//api/v3
  tags: Mobile, Technology, internet, Sports, Athletes, Relative Data, Service API,
    New, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/strava/master/_listings/strava/activitiesid-get-openapi.md
- name: Strava API v3 - Update Activity
  x-api-slug: activitiesid-put
  description: Updates the given activity that is owned by the authenticated athlete.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28739-strava.jpg
  humanURL: https://developers.strava.com
  baseURL: https://www.strava.com//api/v3
  tags: Mobile, Technology, internet, Sports, Athletes, Relative Data, Service API,
    New, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/strava/master/_listings/strava/activitiesid-put-openapi.md
- name: Strava API v3 - List Athlete Activities
  x-api-slug: athleteactivities-get
  description: Returns the activities of an athlete for a specific identifier.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28739-strava.jpg
  humanURL: https://developers.strava.com
  baseURL: https://www.strava.com//api/v3
  tags: Mobile, Technology, internet, Sports, Athletes, Relative Data, Service API,
    New, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/strava/master/_listings/strava/athleteactivities-get-openapi.md
- name: Strava API v3 - List Activity Laps
  x-api-slug: activitiesidlaps-get
  description: Returns the laps of an activity identified by an identifier.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28739-strava.jpg
  humanURL: https://developers.strava.com
  baseURL: https://www.strava.com//api/v3
  tags: Mobile, Technology, internet, Sports, Athletes, Relative Data, Service API,
    New, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/strava/master/_listings/strava/activitiesidlaps-get-openapi.md
- name: Strava API v3 - Get Activity Zones
  x-api-slug: activitiesidzones-get
  description: Premium Feature. Returns the zones of a given activity.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28739-strava.jpg
  humanURL: https://developers.strava.com
  baseURL: https://www.strava.com//api/v3
  tags: Mobile, Technology, internet, Sports, Athletes, Relative Data, Service API,
    New, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/strava/master/_listings/strava/activitiesidzones-get-openapi.md
- name: Strava API v3 - List Activity Comments
  x-api-slug: activitiesidcomments-get
  description: Returns the comments on the given activity.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28739-strava.jpg
  humanURL: https://developers.strava.com
  baseURL: https://www.strava.com//api/v3
  tags: Mobile, Technology, internet, Sports, Athletes, Relative Data, Service API,
    New, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/strava/master/_listings/strava/activitiesidcomments-get-openapi.md
- name: Strava API v3 - List Activity Kudoers
  x-api-slug: activitiesidkudos-get
  description: Returns the athletes who kudoed an activity identified by an identifier.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28739-strava.jpg
  humanURL: https://developers.strava.com
  baseURL: https://www.strava.com//api/v3
  tags: Mobile, Technology, internet, Sports, Athletes, Relative Data, Service API,
    New, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/strava/master/_listings/strava/activitiesidkudos-get-openapi.md
- name: Strava API v3 - Get Club
  x-api-slug: clubsid-get
  description: Returns a given club using its identifier.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28739-strava.jpg
  humanURL: https://developers.strava.com
  baseURL: https://www.strava.com//api/v3
  tags: Mobile, Technology, internet, Sports, Athletes, Relative Data, Service API,
    New, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/strava/master/_listings/strava/clubsid-get-openapi.md
- name: Strava API v3 - List Club Members
  x-api-slug: clubsidmembers-get
  description: Returns a list of the athletes who are members of a given club.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28739-strava.jpg
  humanURL: https://developers.strava.com
  baseURL: https://www.strava.com//api/v3
  tags: Mobile, Technology, internet, Sports, Athletes, Relative Data, Service API,
    New, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/strava/master/_listings/strava/clubsidmembers-get-openapi.md
- name: Strava API v3 - List Club Administrators.
  x-api-slug: clubsidadmins-get
  description: Returns a list of the administrators of a given club.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28739-strava.jpg
  humanURL: https://developers.strava.com
  baseURL: https://www.strava.com//api/v3
  tags: Mobile, Technology, internet, Sports, Athletes, Relative Data, Service API,
    New, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/strava/master/_listings/strava/clubsidadmins-get-openapi.md
- name: Strava API v3 - List Club Activities
  x-api-slug: clubsidactivities-get
  description: Retrieve recent activities from members of a specific club. The authenticated
    athlete must belong to the requested club in order to hit this endpoint. Pagination
    is supported. Enhanced Privacy Mode is respected for all activities.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28739-strava.jpg
  humanURL: https://developers.strava.com
  baseURL: https://www.strava.com//api/v3
  tags: Mobile, Technology, internet, Sports, Athletes, Relative Data, Service API,
    New, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/strava/master/_listings/strava/clubsidactivities-get-openapi.md
- name: Strava API v3 - Join Club
  x-api-slug: clubsidjoin-post
  description: Adds the authenticated athlete to the club's membership.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28739-strava.jpg
  humanURL: https://developers.strava.com
  baseURL: https://www.strava.com//api/v3
  tags: Mobile, Technology, internet, Sports, Athletes, Relative Data, Service API,
    New, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/strava/master/_listings/strava/clubsidjoin-post-openapi.md
- name: Strava API v3 - Leave Club
  x-api-slug: clubsidleave-post
  description: Removes the authenticated athlete from the club's membership.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28739-strava.jpg
  humanURL: https://developers.strava.com
  baseURL: https://www.strava.com//api/v3
  tags: Mobile, Technology, internet, Sports, Athletes, Relative Data, Service API,
    New, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/strava/master/_listings/strava/clubsidleave-post-openapi.md
- name: Strava API v3 - List Athlete Clubs
  x-api-slug: athleteclubs-get
  description: Returns a list of the clubs whose membership includes the authenticated
    athlete.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28739-strava.jpg
  humanURL: https://developers.strava.com
  baseURL: https://www.strava.com//api/v3
  tags: Mobile, Technology, internet, Sports, Athletes, Relative Data, Service API,
    New, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/strava/master/_listings/strava/athleteclubs-get-openapi.md
- name: Strava API v3 - Get Equipment
  x-api-slug: gearid-get
  description: Returns an equipment using its identifier.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28739-strava.jpg
  humanURL: https://developers.strava.com
  baseURL: https://www.strava.com//api/v3
  tags: Mobile, Technology, internet, Sports, Athletes, Relative Data, Service API,
    New, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/strava/master/_listings/strava/gearid-get-openapi.md
- name: Strava API v3 - Get Route
  x-api-slug: routesid-get
  description: Returns a route using its identifier.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28739-strava.jpg
  humanURL: https://developers.strava.com
  baseURL: https://www.strava.com//api/v3
  tags: Mobile, Technology, internet, Sports, Athletes, Relative Data, Service API,
    New, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/strava/master/_listings/strava/routesid-get-openapi.md
- name: Strava API v3 - List Athlete Routes
  x-api-slug: athletesidroutes-get
  description: Returns a list of the routes created by the authenticated athlete using
    their athlete ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28739-strava.jpg
  humanURL: https://developers.strava.com
  baseURL: https://www.strava.com//api/v3
  tags: Mobile, Technology, internet, Sports, Athletes, Relative Data, Service API,
    New, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/strava/master/_listings/strava/athletesidroutes-get-openapi.md
- name: Strava API v3 - Upload Activity
  x-api-slug: uploads-post
  description: Uploads a new data file to create an activity from.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28739-strava.jpg
  humanURL: https://developers.strava.com
  baseURL: https://www.strava.com//api/v3
  tags: Mobile, Technology, internet, Sports, Athletes, Relative Data, Service API,
    New, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/strava/master/_listings/strava/uploads-post-openapi.md
- name: Strava API v3 - Get Upload
  x-api-slug: uploadsuploadid-get
  description: Returns an upload for a given identifier.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28739-strava.jpg
  humanURL: https://developers.strava.com
  baseURL: https://www.strava.com//api/v3
  tags: Mobile, Technology, internet, Sports, Athletes, Relative Data, Service API,
    New, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/strava/master/_listings/strava/uploadsuploadid-get-openapi.md
- name: Strava API v3 - Get Activity Streams
  x-api-slug: activitiesidstreams-get
  description: Returns the given activity's streams.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28739-strava.jpg
  humanURL: https://developers.strava.com
  baseURL: https://www.strava.com//api/v3
  tags: Mobile, Technology, internet, Sports, Athletes, Relative Data, Service API,
    New, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/strava/master/_listings/strava/activitiesidstreams-get-openapi.md
- name: Strava API v3 - Get segment effort streams
  x-api-slug: segment-effortsidstreams-get
  description: Returns a set of streams for a segment effort completed by the authenticated
    athlete.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28739-strava.jpg
  humanURL: https://developers.strava.com
  baseURL: https://www.strava.com//api/v3
  tags: Mobile, Technology, internet, Sports, Athletes, Relative Data, Service API,
    New, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/strava/master/_listings/strava/segment-effortsidstreams-get-openapi.md
- name: Strava API v3 - Get Segment Streams
  x-api-slug: segmentsidstreams-get
  description: Returns the given segment's streams.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28739-strava.jpg
  humanURL: https://developers.strava.com
  baseURL: https://www.strava.com//api/v3
  tags: Mobile, Technology, internet, Sports, Athletes, Relative Data, Service API,
    New, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/strava/master/_listings/strava/segmentsidstreams-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://storecove.api.gallery.streamdata.io
- type: x-api-stack
  url: http://strava.stack.network
- type: x-code
  url: https://developers.strava.com/docs/#client-code
- type: x-crunchbase
  url: https://crunchbase.com/organization/strava
- type: x-documentation
  url: https://developers.strava.com/docs/reference/
- type: x-email
  url: developers@strava.com
- type: x-email
  url: dpo@strava.com
- type: x-email
  url: ip@strava.com
- type: x-github
  url: https://github.com/strava
- type: x-openapi
  url: https://developers.strava.com/swagger/swagger.json
- type: x-twitter
  url: https://twitter.com/Strava
- type: x-webhook
  url: https://developers.strava.com/docs/webhooks/
- type: x-developer
  url: https://developers.strava.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---