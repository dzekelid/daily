---
name: Weatherbit
x-slug: weatherbit
description: Our mission at Weatherbit.io is pretty simple. It is to provide the highest
  quality weather forecasts, observations, and historical weather data at the best
  price. We constantly improve our platform every day. Our Weather APIs grow with
  you. Have a feature request? Let us know on our Support Forum! Our commitment to
  data quality is unparalleled. Our forecast system uses global forecast models (GFS/ECMWF),
  in combination with local short range high resolution models to derive the most
  accurate, and relevant forecast apis on the web.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
x-kinRank: "8"
x-alexaRank: "0"
tags: Daily
created: "2018-06-18"
modified: "2018-06-18"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit/apis.md
specificationVersion: "0.14"
apis:
- name: Weatherbit Get Bulk History Daily City Country
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a city in the format of City,ST
    or City. The state, and country parameters can be provided to make the search
    more accurate.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//bulk/history/daily?city={city}&country={country}
  tags: Weather,Bulk, History, Daily, City, City, &country, Country
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit/bulkhistorydailycitycitycountrycountry-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit/bulkhistorydailycitycitycountrycountry-get-openapi.md
- name: Weatherbit Get Bulk History Daily City
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a City ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//bulk/history/daily?city_id={city_id}
  tags: Weather,Bulk, History, Daily, City, , City
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit/bulkhistorydailycity-idcity-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit/bulkhistorydailycity-idcity-id-get-openapi.md
- name: Weatherbit Get Bulk History Daily IP
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given IP Address, or auto.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//bulk/history/daily?ip={ip}
  tags: Weather,Bulk, History, Daily, Ip, Ip
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit/bulkhistorydailyipip-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit/bulkhistorydailyipip-get-openapi.md
- name: Weatherbit Get Bulk History Daily Lat Lon
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a lat, and lon.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//bulk/history/daily?lat={lat}&lon={lon}
  tags: Weather,Bulk, History, Daily, Lat, Lat, &lon, Lon
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit/bulkhistorydailylatlatlonlon-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit/bulkhistorydailylatlatlonlon-get-openapi.md
- name: Weatherbit Get Bulk History Daily Postal Code
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a Postal Code.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//bulk/history/daily?postal_code={postal_code}
  tags: Weather,Bulk, History, Daily, Postal, Code, Postal, Code
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit/bulkhistorydailypostal-codepostal-code-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit/bulkhistorydailypostal-codepostal-code-get-openapi.md
- name: Weatherbit Get Bulk History Daily Station
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a station ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//bulk/history/daily?station={station}
  tags: Weather,Bulk, History, Daily, Station, Station
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit/bulkhistorydailystationstation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit/bulkhistorydailystationstation-get-openapi.md
- name: Weatherbit Get Forecast Daily City & Country
  x-api-slug: weatherbit
  description: '**(REQUIRED: Basic Plan or Higher)** Returns a daily forecast, where
    each point represents one day (24hr) period. Every point has a datetime string
    in the format "YYYY-MM-DD". One day begins at 00:00 UTC, and ends at 23:59 UTC.
    Accepts a city in the format of City,ST or City. The state, and country parameters
    can be provided to make the search more accurate.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/daily?city={city}&country={country}
  tags: Weather,Forecast, Daily, City, City, &country, Country
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit/forecastdailycitycitycountrycountry-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit/forecastdailycitycitycountrycountry-get-openapi.md
- name: Weatherbit Get Forecast Daily City
  x-api-slug: weatherbit
  description: '**(REQUIRED: Basic Plan or Higher)** Returns a daily forecast, where
    each point represents one day (24hr) period. Every point has a datetime string
    in the format "YYYY-MM-DD". One day begins at 00:00 UTC, and ends at 23:59 UTC.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/daily?city_id={city_id}
  tags: Weather,Forecast, Daily, City, , City
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit/forecastdailycity-idcity-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit/forecastdailycity-idcity-id-get-openapi.md
- name: Weatherbit Get Forecast Daily IP
  x-api-slug: weatherbit
  description: '**(REQUIRED: Basic Plan or Higher)** Returns a daily forecast, where
    each point represents one day (24hr) period. Every point has a datetime string
    in the format "YYYY-MM-DD". One day begins at 00:00 UTC, and ends at 23:59 UTC.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/daily?ip={ip}
  tags: Weather,Forecast, Daily, Ip, Ip
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit/forecastdailyipip-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit/forecastdailyipip-get-openapi.md
- name: Weatherbit Get Forecast Daily Lat & Lon
  x-api-slug: weatherbit
  description: '**(REQUIRED: Basic Plan or Higher)** Returns a daily forecast, where
    each point represents one day (24hr) period. Every point has a datetime string
    in the format "YYYY-MM-DD". One day begins at 00:00 UTC, and ends at 23:59 UTC.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/daily?lat={lat}&lon={lon}
  tags: Weather,Forecast, Daily, Lat, Lat, &lon, Lon
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit/forecastdailylatlatlonlon-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit/forecastdailylatlatlonlon-get-openapi.md
- name: Weatherbit Get Forecast Daily Postla Code Code
  x-api-slug: weatherbit
  description: '**(REQUIRED: Basic Plan or Higher)** Returns a daily forecast, where
    each point represents one day (24hr) period. Every point has a datetime string
    in the format "YYYY-MM-DD". One day begins at 00:00 UTC, and ends at 23:59 UTC.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/daily?postal_code={postal_code}
  tags: Weather,Forecast, Daily, Postal, Code, Postal, Code
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit/forecastdailypostal-codepostal-code-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit/forecastdailypostal-codepostal-code-get-openapi.md
- name: Weatherbit Get History Daily City & Country
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a city in the format of City,ST
    or City. The state, and country parameters can be provided to make the search
    more accurate. **(LIMIT 1 day for Low Volume plans. LIMIT 7 days for Basic/Developer.
    LIMIT 30 days for Advanced/Advanced+/Enterprise)**
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//history/daily?city={city}&country={country}
  tags: Weather,History, Daily, City, City, &country, Country
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit/historydailycitycitycountrycountry-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit/historydailycitycitycountrycountry-get-openapi.md
- name: Weatherbit Get History Daily City
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a City ID. **(LIMIT 1 day for
    Low Volume plans. LIMIT 7 days for Basic/Developer. LIMIT 30 days for Advanced/Advanced+/Enterprise)**
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//history/daily?city_id={city_id}
  tags: Weather,History, Daily, City, , City
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit/historydailycity-idcity-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit/historydailycity-idcity-id-get-openapi.md
- name: Weatherbit Get History Daily IP
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given IP Address, or auto. **(LIMIT
    1 day for Low Volume plans. LIMIT 7 days for Basic/Developer. LIMIT 30 days for
    Advanced/Advanced+/Enterprise)**
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//history/daily?ip={ip}
  tags: Weather,History, Daily, Ip, Ip
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit/historydailyipip-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit/historydailyipip-get-openapi.md
- name: Weatherbit Get History Daily Lat & Lon
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a lat, and lon. **(LIMIT 1
    day for Low Volume plans. LIMIT 7 days for Basic/Developer. LIMIT 30 days for
    Advanced/Advanced+/Enterprise)**
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//history/daily?lat={lat}&lon={lon}
  tags: Weather,History, Daily, Lat, Lat, &lon, Lon
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit/historydailylatlatlonlon-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit/historydailylatlatlonlon-get-openapi.md
- name: Weatherbit Get History Daily Postla Code Code
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a Postal Code. **(LIMIT 1 day
    for Low Volume plans. LIMIT 7 days for Basic/Developer. LIMIT 30 days for Advanced/Advanced+/Enterprise)**
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//history/daily?postal_code={postal_code}
  tags: Weather,History, Daily, Postal, Code, Postal, Code
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit/historydailypostal-codepostal-code-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit/historydailypostal-codepostal-code-get-openapi.md
- name: Weatherbit Get History Daily Station Station
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a station ID. **(LIMIT 1 day
    for Low Volume plans. LIMIT 7 days for Basic/Developer. LIMIT 30 days for Advanced/Advanced+/Enterprise)**
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//history/daily?station={station}
  tags: Weather,History, Daily, Station, Station
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit/historydailystationstation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit/historydailystationstation-get-openapi.md
- name: Weatherbit
  x-api-slug: weatherbit
  description: Our mission at Weatherbit.io is pretty simple. It is to provide the
    highest quality weather forecasts, observations, and historical weather data at
    the best price. We constantly improve our platform every day. Our Weather APIs
    grow with you. Have a feature request? Let us know on our Support Forum! Our commitment
    to data quality is unparalleled. Our forecast system uses global forecast models
    (GFS/ECMWF), in combination with local short range high resolution models to derive
    the most accurate, and relevant forecast apis on the web.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0
  tags: Daily
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/daily/master/_listings/weatherbit/openapi.md
x-common:
- type: x-blog
  url: https://www.weatherbit.io/blog
- type: x-contact-form
  url: https://www.weatherbit.io/contact
- type: x-documentation
  url: https://www.weatherbit.io/api
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