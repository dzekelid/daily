---
swagger: "2.0"
x-collection-name: ClimaCell
x-complete: 1
info:
  title: ClimaCell API
  description: the-climacell-rest-api-provides-access-to-high-resolution-weather-data-for-locations-across-the-u-s--with-global-data-coming-soon--it-uses-https-and-requires-an-access-token-key--the-api-requests-carry-query-parameters-and-the-responses-return-results-in-json-format-
  version: 1.0.0
host: api2.climacell.co
basePath: /v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /daily:
    post:
      summary: Post Daily
      description: "### Daily (Coming Soon)\nThe ```\u200Bdaily\u200B``` API call
        provides the daily forecast with weather parameter summaries for the next
        16 \u200Bdays\u200B. The weather data includes daily minimum and maximum values
        for temperature, feels-like, dew point, pressure, humidity, and visibility,
        along with accumulated precipitation, list of precipitation types and wind
        information."
      operationId: -daily-coming-soonthe-daily-api-call-provides-the-daily-forecast-with-weather-parameter-summaries-fo
      x-api-path-slug: daily-post
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Daily
---