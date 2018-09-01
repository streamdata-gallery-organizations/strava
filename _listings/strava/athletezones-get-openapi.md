---
swagger: "2.0"
x-collection-name: Strava
x-complete: 0
info:
  title: Strava Get Zones
  description: Returns the the authenticated athlete's heart rate and power zones.
  version: 1.0.0
host: www.strava.com
basePath: /api/v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /athletes/{id}/stats:
    get:
      summary: Get Athlete Stats
      description: Returns the activity stats of an athlete.
      operationId: getStats
      x-api-path-slug: athletesidstats-get
      parameters:
      - in: path
        name: id
        description: The identifier of the athlete
      - in: query
        name: No Name
      responses:
        200:
          description: Successful response
      tags:
      - Sports
      - Athlete
      - Stats
  /athlete:
    get:
      summary: Get Authenticated Athlete
      description: Returns the currently authenticated athlete.
      operationId: getLoggedInAthlete
      x-api-path-slug: athlete-get
      responses:
        200:
          description: Successful response
      tags:
      - Sports
      - Authenticated
      - Athlete
    put:
      summary: Update Athlete
      description: Update the currently authenticated athlete.
      operationId: updateLoggedInAthlete
      x-api-path-slug: athlete-put
      parameters:
      - in: body
        name: body
        description: The athlete entity to update
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: Successful response
      tags:
      - Sports
      - Athlete
  /athlete/zones:
    get:
      summary: Get Zones
      description: Returns the the authenticated athlete's heart rate and power zones.
      operationId: getLoggedInAthleteZones
      x-api-path-slug: athletezones-get
      responses:
        200:
          description: Successful response
      tags:
      - Sports
      - Zones
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