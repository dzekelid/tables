---
swagger: "2.0"
x-collection-name: Coord
x-complete: 0
info:
  title: Coord Bike Share API Get detailed information on a bike system, as a GeoJSON
    feature.
  description: |-
    Bike systems are individual bike share systems, often per-region.

    Information is returned as a GeoJSON Feature. The geometry of the GeoJSON Feature is
    a MultiPolygon that defines the system's operational area. All bike systems have an
    operational area, in which bikes may be found and parked.
    For systems that require bikes be docked, this area is somewhat arbitrary, as bikes are
    only found at stations. In this case, the operational area is roughly the city or
    jurisdiction that the system covers.
    For semi-dockless and dockless systems that allow bikes to be parked anywhere, the
    operational area is very important and strictly defined. Often there are extra fees for
    parking outside of the operational area (also known as a "catchment area"), and almost all
    bikes should be within the area.

    These bike system types are reflected in the `station_type` property.
    * `dock` - All bikes must be taken from and returned to a dock.
    * `dockless` - All bikes are only dockless.
    * `dockless_with_hub` - Bikes may be dockless, or taken from or returned to a hub.
    A hub can be an area rather than a discrete station, where a bike can be returned and
    locked but not explicitly docked. The total price of a rental may change based on whether
    a bike is returned to a hub or not.

    Areas are returned as a GeoJSON MultiPolygon since areas may be discontiguous or have
    holes.

    ### Example

    #### Request:
    `curl -G "https://api.coord.co/v1/bike/system/CitiBike?access_key="`

    #### Response:
    ```
    {
      "type": "Feature",
      "geometry": {
          "type": "MultiPolygon",
          "coordinates": [
            [
              [ [-74.00, 40.70], [-74.00, 40.80], [-73.90, 40.80], ..., [-74.00, 40.70] ]
            ],
            ...,
            [
              [ [-73.00, 41.70], [-73.00, 41.80], [-72.90, 41.80], ..., [-73.00, 41.70] ],
              [ [-72.98, 41.75], [-72.98, 41.78], [-72.95, 41.78], ..., [-72.98, 41.75] ]
            ]
          ]
        },
      "id": "CitiBike",
      "properties": {
        "email": "support@coord.co",
        "phone_number": "+6789998212",
        "station_type": "dock",
        "is_transactable": "false"
      }
    }
    ```
  version: 1.0.0
host: api.coord.co
basePath: /v1/bike
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /system/{system_id}:
    get:
      summary: Get detailed information on a bike system, as a GeoJSON feature.
      description: |-
        Bike systems are individual bike share systems, often per-region.

        Information is returned as a GeoJSON Feature. The geometry of the GeoJSON Feature is
        a MultiPolygon that defines the system's operational area. All bike systems have an
        operational area, in which bikes may be found and parked.
        For systems that require bikes be docked, this area is somewhat arbitrary, as bikes are
        only found at stations. In this case, the operational area is roughly the city or
        jurisdiction that the system covers.
        For semi-dockless and dockless systems that allow bikes to be parked anywhere, the
        operational area is very important and strictly defined. Often there are extra fees for
        parking outside of the operational area (also known as a "catchment area"), and almost all
        bikes should be within the area.

        These bike system types are reflected in the `station_type` property.
        * `dock` - All bikes must be taken from and returned to a dock.
        * `dockless` - All bikes are only dockless.
        * `dockless_with_hub` - Bikes may be dockless, or taken from or returned to a hub.
        A hub can be an area rather than a discrete station, where a bike can be returned and
        locked but not explicitly docked. The total price of a rental may change based on whether
        a bike is returned to a hub or not.

        Areas are returned as a GeoJSON MultiPolygon since areas may be discontiguous or have
        holes.

        ### Example

        #### Request:
        `curl -G "https://api.coord.co/v1/bike/system/CitiBike?access_key="`

        #### Response:
        ```
        {
          "type": "Feature",
          "geometry": {
              "type": "MultiPolygon",
              "coordinates": [
                [
                  [ [-74.00, 40.70], [-74.00, 40.80], [-73.90, 40.80], ..., [-74.00, 40.70] ]
                ],
                ...,
                [
                  [ [-73.00, 41.70], [-73.00, 41.80], [-72.90, 41.80], ..., [-73.00, 41.70] ],
                  [ [-72.98, 41.75], [-72.98, 41.78], [-72.95, 41.78], ..., [-72.98, 41.75] ]
                ]
              ]
            },
          "id": "CitiBike",
          "properties": {
            "email": "support@coord.co",
            "phone_number": "+6789998212",
            "station_type": "dock",
            "is_transactable": "false"
          }
        }
        ```
      operationId: get_bike_system
      x-api-path-slug: systemsystem-id-get
      parameters:
      - in: query
        name: access_key
        description: The API access key for the request
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Detailed
      - Information
      - "On"
      - Bike
      - System
      - ""
      - As
      - GeoJSON
      - Feature
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