---
swagger: "2.0"
info:
  title: AWS Route 53 API Get Traffic Policy
  version: 1.0.0
  description: Gets information about a specific traffic policy version.Send a GET
    request to the /Amazon Route 53 APIversion/trafficpolicy resource.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /2013-04-01/trafficpolicy/Id/Version:
    get:
      summary: Get Traffic Policy
      description: Gets information about a specific traffic policy version
      operationId: gettrafficpolicy
      parameters:
      - in: path
        name: Id
        description: The ID of the traffic policy that you want to get information
          about
        type: string
      responses:
        200:
          description: OK
      tags:
      - traffic policies
definitions: []
x-collection-name: AWS Route 53
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