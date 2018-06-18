---
swagger: "2.0"
x-collection-name: ClimaCell
x-complete: 0
info:
  title: ClimaCell Post Daily
  description: "### Daily (Coming Soon)\nThe ```\u200Bdaily\u200B``` API call provides
    the daily forecast with weather parameter summaries for the next 16 \u200Bdays\u200B.
    The weather data includes daily minimum and maximum values for temperature, feels-like,
    dew point, pressure, humidity, and visibility, along with accumulated precipitation,
    list of precipitation types and wind information."
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