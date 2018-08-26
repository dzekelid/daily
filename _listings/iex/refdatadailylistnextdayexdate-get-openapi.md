---
swagger: "2.0"
x-collection-name: IEX
x-complete: 0
info:
  title: IEX Trading API Next Day Ex Date
  description: Refer to the Daily list specification for futher details.
  termsOfService: https://iextrading.com/api-terms/
  version: 1.0.0
host: api.iextrading.com
basePath: /1.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /ref-data/daily-list/symbol-directory:
    get:
      summary: Corporate Actions
      description: Refer to the Daily list specification for futher details.
      operationId: iex-corporate-actions
      x-api-path-slug: refdatadailylistsymboldirectory-get
      parameters:
      - in: query
        name: format
        description: Parameter is optional Value can be csv or psv When parameter
          is not present, format defaults to JSON
      - in: query
        name: token
        description: Parameter is optional Value is the API token from your IEX user
          account If you have been permissioned for CUSIP information you&rsquo;ll
          receive a CUSIP field, othewise data defaults to exclude CUSIP
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Daily List
  /ref-data/daily-list/next-day-ex-date:
    get:
      summary: Next Day Ex Date
      description: Refer to the Daily list specification for futher details.
      operationId: iex-next-day-ex-date
      x-api-path-slug: refdatadailylistnextdayexdate-get
      parameters:
      - in: query
        name: format
        description: Parameter is optional Value can be csv or psv When parameter
          is not present, format defaults to JSON
      - in: query
        name: token
        description: Parameter is optional Value is the API token from your IEX user
          account If you have been permissioned for CUSIP information you&rsquo;ll
          receive a CUSIP field, othewise data defaults to exclude CUSIP
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Daily List
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