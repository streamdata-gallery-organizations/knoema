---
swagger: "2.0"
info:
  title: Knoema
  description: You don&rsquo;t need to be a developer to get started. We made a number
    of useful platform features available as ready to use widgets. You can put a dashboard
    or presentation with any visualization/content you like and then embed it in your
    site or blog in a few minutes.  Such an approach requires no programming skills
    at all, just basic understanding of HTML. Refer to Widgets sections for more information
    on this topic. Knoema is a truly open platform.  In addition to our own APIs we
    support several formats widely acknowledged by industry such as OData and SDMX.  If
    you already have tools/clients utilizing data in these formats you can add Knoema
    support very easily. More information can be found in Open Data section. For enthusiasts
    and hardcore developers Knoema offers extensive Knoema API providing access to
    all platform capabilities. Start with getting familiar with core Knoema concepts.
    Then proceed to Applications section to find step-by-step tutorials, detailed
    documentation and sample apps.
  version: 1.0.0
host: knoema.com
basePath: /api/1.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /search:
    get:
      summary: Search by keyword
      description: This namespace provides search details for data accessible by that
        user
      operationId: search
      parameters:
      - in: query
        name: correct
        description: correct (default true) - correct mistakes in the query or not
        type: string
        format: string
      - in: query
        name: count
        description: count (default 100) - number results count [0
        type: string
        format: string
      - in: query
        name: query
        description: 'search query for which data is required '
        type: string
        format: string
      - in: query
        name: scope
        description: String to specify the type of search results
        type: string
        format: string
      - in: query
        name: start
        description: start (default 0) - number of the first result [0
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - datasets
      - search
definitions: []
x-collection-name: Knoema
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