---
swagger: "2.0"
x-collection-name: aWhere
x-complete: 0
info:
  title: aWhere Daily Observations
  description: "####Request\nThis API call gets the weather at a field location.\n\nThe
    default URL will get the last seven days of actual weather observations. You can
    add dates to the end of the URL to get the weather for a specific range of days,
    like so: \n\n`/v2/weather/fields/field1/observations/2015-08-01` gets a single
    day\n`/v2/weather/fields/field1/observations/2015-08-01,2015-08-15` gets everything
    from August 1-15\n\nYou can customize the response payload using query string
    parameters. Learn more in the [Daily Observations Documentation](http://developer.awhere.com/api/reference/weather/observations).\n\n_Tip:
    Remember to use a field ID that exists in your account. By default, this collection
    uses a default field ID of 'field1'_\n\n\n####Security\nThis API call uses the
    security Access Token that is retrieved with the \"Get a Token\" request. If you
    run that request first, it will save a token to Postman and this API will use
    it automatically. You can also see where the token should normally go by clicking
    the \"Headers\" tab below. The Authorization header holds the token, replacing
    the \"{{aWhereAccessToken}}\" part."
  version: 1.0.0
host: api.awhere.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v2/weather/fields/field1/observations:
    get:
      summary: Daily Observations
      description: "####Request\nThis API call gets the weather at a field location.\n\nThe
        default URL will get the last seven days of actual weather observations. You
        can add dates to the end of the URL to get the weather for a specific range
        of days, like so: \n\n`/v2/weather/fields/field1/observations/2015-08-01`
        gets a single day\n`/v2/weather/fields/field1/observations/2015-08-01,2015-08-15`
        gets everything from August 1-15\n\nYou can customize the response payload
        using query string parameters. Learn more in the [Daily Observations Documentation](http://developer.awhere.com/api/reference/weather/observations).\n\n_Tip:
        Remember to use a field ID that exists in your account. By default, this collection
        uses a default field ID of 'field1'_\n\n\n####Security\nThis API call uses
        the security Access Token that is retrieved with the \"Get a Token\" request.
        If you run that request first, it will save a token to Postman and this API
        will use it automatically. You can also see where the token should normally
        go by clicking the \"Headers\" tab below. The Authorization header holds the
        token, replacing the \"{{aWhereAccessToken}}\" part."
      operationId: V2WeatherFieldsField1ObservationsGet
      x-api-path-slug: v2weatherfieldsfield1observations-get
      responses:
        200:
          description: OK
      tags:
      - Agriculture
      - Daily
      - Observations
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