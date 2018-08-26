---
name: Weatherbit.io
x-slug: weatherbit-io
description: Our Weather API is the most powerful Weather data API on the web. Sign
  up for our free Weather API, and upgrade as your weather data needs grow!
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
x-kinRank: "8"
x-alexaRank: "1016253"
tags: Daily
created: "2018-08-26"
modified: "2018-08-26"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit-io/apis.md
specificationVersion: "0.14"
apis:
- name: Weatherbit - Get Bulk History Daily City Country
  x-api-slug: bulkhistorydailycitycitycountrycountry-get
  description: Returns Historical Observations - Given a city in the format of City,ST
    or City. The state, and country parameters can be provided to make the search
    more accurate.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0
  tags: Weather, SaaS, Broadcasts, General Data, Service API, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit-io/bulkhistorydailycitycitycountrycountry-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit-io/bulkhistorydailycitycitycountrycountry-get-openapi.md
- name: Weatherbit - Get Bulk History Daily City
  x-api-slug: bulkhistorydailycity-idcity-id-get
  description: Returns Historical Observations - Given a City ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0
  tags: Weather, SaaS, Broadcasts, General Data, Service API, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit-io/bulkhistorydailycity-idcity-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit-io/bulkhistorydailycity-idcity-id-get-openapi.md
- name: Weatherbit - Get Bulk History Daily IP
  x-api-slug: bulkhistorydailyipip-get
  description: Returns Historical Observations - Given IP Address, or auto.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0
  tags: Weather, SaaS, Broadcasts, General Data, Service API, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit-io/bulkhistorydailyipip-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit-io/bulkhistorydailyipip-get-openapi.md
- name: Weatherbit - Get Bulk History Daily Lat Lon
  x-api-slug: bulkhistorydailylatlatlonlon-get
  description: Returns Historical Observations - Given a lat, and lon.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0
  tags: Weather, SaaS, Broadcasts, General Data, Service API, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit-io/bulkhistorydailylatlatlonlon-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit-io/bulkhistorydailylatlatlonlon-get-openapi.md
- name: Weatherbit - Get Bulk History Daily Postal Code
  x-api-slug: bulkhistorydailypostal-codepostal-code-get
  description: Returns Historical Observations - Given a Postal Code.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0
  tags: Weather, SaaS, Broadcasts, General Data, Service API, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit-io/bulkhistorydailypostal-codepostal-code-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit-io/bulkhistorydailypostal-codepostal-code-get-openapi.md
- name: Weatherbit - Get Bulk History Daily Station
  x-api-slug: bulkhistorydailystationstation-get
  description: Returns Historical Observations - Given a station ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0
  tags: Weather, SaaS, Broadcasts, General Data, Service API, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit-io/bulkhistorydailystationstation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit-io/bulkhistorydailystationstation-get-openapi.md
- name: Weatherbit - Get Forecast Daily City & Country
  x-api-slug: forecastdailycitycitycountrycountry-get
  description: '**(REQUIRED: Basic Plan or Higher)** Returns a daily forecast, where
    each point represents one day (24hr) period. Every point has a datetime string
    in the format "YYYY-MM-DD". One day begins at 00:00 UTC, and ends at 23:59 UTC.
    Accepts a city in the format of City,ST or City. The state, and country parameters
    can be provided to make the search more accurate.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0
  tags: Weather, SaaS, Broadcasts, General Data, Service API, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit-io/forecastdailycitycitycountrycountry-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit-io/forecastdailycitycitycountrycountry-get-openapi.md
- name: Weatherbit - Get Forecast Daily City
  x-api-slug: forecastdailycity-idcity-id-get
  description: '**(REQUIRED: Basic Plan or Higher)** Returns a daily forecast, where
    each point represents one day (24hr) period. Every point has a datetime string
    in the format "YYYY-MM-DD". One day begins at 00:00 UTC, and ends at 23:59 UTC.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0
  tags: Weather, SaaS, Broadcasts, General Data, Service API, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit-io/forecastdailycity-idcity-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit-io/forecastdailycity-idcity-id-get-openapi.md
- name: Weatherbit - Get Forecast Daily IP
  x-api-slug: forecastdailyipip-get
  description: '**(REQUIRED: Basic Plan or Higher)** Returns a daily forecast, where
    each point represents one day (24hr) period. Every point has a datetime string
    in the format "YYYY-MM-DD". One day begins at 00:00 UTC, and ends at 23:59 UTC.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0
  tags: Weather, SaaS, Broadcasts, General Data, Service API, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit-io/forecastdailyipip-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit-io/forecastdailyipip-get-openapi.md
- name: Weatherbit - Get Forecast Daily Lat & Lon
  x-api-slug: forecastdailylatlatlonlon-get
  description: '**(REQUIRED: Basic Plan or Higher)** Returns a daily forecast, where
    each point represents one day (24hr) period. Every point has a datetime string
    in the format "YYYY-MM-DD". One day begins at 00:00 UTC, and ends at 23:59 UTC.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0
  tags: Weather, SaaS, Broadcasts, General Data, Service API, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit-io/forecastdailylatlatlonlon-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit-io/forecastdailylatlatlonlon-get-openapi.md
- name: Weatherbit - Get Forecast Daily Postla Code Code
  x-api-slug: forecastdailypostal-codepostal-code-get
  description: '**(REQUIRED: Basic Plan or Higher)** Returns a daily forecast, where
    each point represents one day (24hr) period. Every point has a datetime string
    in the format "YYYY-MM-DD". One day begins at 00:00 UTC, and ends at 23:59 UTC.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0
  tags: Weather, SaaS, Broadcasts, General Data, Service API, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit-io/forecastdailypostal-codepostal-code-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit-io/forecastdailypostal-codepostal-code-get-openapi.md
- name: Weatherbit - Get History Daily City & Country
  x-api-slug: historydailycitycitycountrycountry-get
  description: Returns Historical Observations - Given a city in the format of City,ST
    or City. The state, and country parameters can be provided to make the search
    more accurate. **(LIMIT 1 day for Low Volume plans. LIMIT 7 days for Basic/Developer.
    LIMIT 30 days for Advanced/Advanced+/Enterprise)**
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0
  tags: Weather, SaaS, Broadcasts, General Data, Service API, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit-io/historydailycitycitycountrycountry-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit-io/historydailycitycitycountrycountry-get-openapi.md
- name: Weatherbit - Get History Daily City
  x-api-slug: historydailycity-idcity-id-get
  description: Returns Historical Observations - Given a City ID. **(LIMIT 1 day for
    Low Volume plans. LIMIT 7 days for Basic/Developer. LIMIT 30 days for Advanced/Advanced+/Enterprise)**
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0
  tags: Weather, SaaS, Broadcasts, General Data, Service API, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit-io/historydailycity-idcity-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit-io/historydailycity-idcity-id-get-openapi.md
- name: Weatherbit - Get History Daily IP
  x-api-slug: historydailyipip-get
  description: Returns Historical Observations - Given IP Address, or auto. **(LIMIT
    1 day for Low Volume plans. LIMIT 7 days for Basic/Developer. LIMIT 30 days for
    Advanced/Advanced+/Enterprise)**
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0
  tags: Weather, SaaS, Broadcasts, General Data, Service API, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit-io/historydailyipip-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit-io/historydailyipip-get-openapi.md
- name: Weatherbit - Get History Daily Lat & Lon
  x-api-slug: historydailylatlatlonlon-get
  description: Returns Historical Observations - Given a lat, and lon. **(LIMIT 1
    day for Low Volume plans. LIMIT 7 days for Basic/Developer. LIMIT 30 days for
    Advanced/Advanced+/Enterprise)**
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0
  tags: Weather, SaaS, Broadcasts, General Data, Service API, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit-io/historydailylatlatlonlon-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit-io/historydailylatlatlonlon-get-openapi.md
- name: Weatherbit - Get History Daily Postla Code Code
  x-api-slug: historydailypostal-codepostal-code-get
  description: Returns Historical Observations - Given a Postal Code. **(LIMIT 1 day
    for Low Volume plans. LIMIT 7 days for Basic/Developer. LIMIT 30 days for Advanced/Advanced+/Enterprise)**
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0
  tags: Weather, SaaS, Broadcasts, General Data, Service API, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit-io/historydailypostal-codepostal-code-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit-io/historydailypostal-codepostal-code-get-openapi.md
- name: Weatherbit - Get History Daily Station Station
  x-api-slug: historydailystationstation-get
  description: Returns Historical Observations - Given a station ID. **(LIMIT 1 day
    for Low Volume plans. LIMIT 7 days for Basic/Developer. LIMIT 30 days for Advanced/Advanced+/Enterprise)**
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0
  tags: Weather, SaaS, Broadcasts, General Data, Service API, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit-io/historydailystationstation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit-io/historydailystationstation-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://weather.underground.api.gallery.streamdata.io
- type: x-api-stack
  url: http://weatherbit.io.stack.network
- type: x-blog
  url: https://www.weatherbit.io/blog
- type: x-contact-form
  url: https://www.weatherbit.io/contact
- type: x-crunchbase
  url: https://crunchbase.com/organization/product/weather-it-
- type: x-documentation
  url: https://www.weatherbit.io/api
- type: x-email
  url: support@weatherbit.io
- type: x-github
  url: https://github.com/weatherbit
- type: x-pricing
  url: https://www.weatherbit.io/pricing
- type: x-twitter
  url: https://twitter.com/weatherbitio
- type: x-website
  url: http://weatherbit.io
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---