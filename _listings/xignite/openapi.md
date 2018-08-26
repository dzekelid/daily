---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 1
info:
  title: Xignite VWAP
  description: provides-delayed-and-historical-volumeweightedaverage-price-vwap-information-
  version: 1.0.0
host: www.xignite.com
basePath: xVWAP.json/XigniteVWAP
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /GetHistoricalDailyVWAP:
    get:
      summary: Get Historical Daily VWAP
      description: Returns historical daily VWAP information for a date range
      operationId: GetHistoricalDailyVWAP
      x-api-path-slug: gethistoricaldailyvwap-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Historical
      - Daily
      - VWAP
---