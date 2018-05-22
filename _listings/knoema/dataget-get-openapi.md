---
swagger: "2.0"
x-collection-name: Knoema
x-complete: 0
info:
  title: Knoema API Get data
  description: This endpoint returns observation data for the given filter.
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
  /meta/dataset:
    get:
      summary: List of datasets
      description: Returns the list of datasets
      operationId: listOfDatasets
      x-api-path-slug: metadataset-get
      responses:
        200:
          description: OK
      tags:
      - Datasets
  /meta/dataset/{dataset id}:
    get:
      summary: Dataset details
      description: Lists out details of a particular dataset.
      operationId: datasetDetails
      x-api-path-slug: metadatasetdataset-id-get
      responses:
        200:
          description: OK
      tags:
      - Datasets
  /meta/dataset/{datasetId}/dimension/{dimensionId}:
    get:
      summary: Dimension
      description: Lists out the given dataset's dimension details.
      operationId: datasetDimensions
      x-api-path-slug: metadatasetdatasetiddimensiondimensionid-get
      responses:
        200:
          description: OK
      tags:
      - Datasets
      - Dimensions
  /meta/group/{groupKey}:
    get:
      summary: Dimension Group
      description: 'This endpoint used to list/add/edit/delete groups in dimensions.
        The functionality of endpoint depends on HTTP method: GET, POST, PUT or DELETE.'
      operationId: dimensionGroup
      x-api-path-slug: metagroupgroupkey-get
      responses:
        200:
          description: OK
      tags:
      - Groups
      - Dimensions
  /frontend/tags:
    get:
      summary: List of tags
      description: Lists out all the public tags present in the system
      operationId: getTags
      x-api-path-slug: frontendtags-get
      responses:
        200:
          description: OK
      tags:
      - Tags
  /data/dataset/{dataset id}:
    get:
      summary: Get timeseries list
      description: For the given dataset, this endpoint returns time series list for
        all the available frequencies with the combination of all the dimension members.
      operationId: getTimeseriesList
      x-api-path-slug: datadatasetdataset-id-get
      parameters:
      - in: path
        name: dataset id
        description: 'Unique dataset identifier '
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Datasets
      - Time Series
  /data/get:
    get:
      summary: Get data
      description: This endpoint returns observation data for the given filter.
      operationId: getData
      x-api-path-slug: dataget-get
      parameters:
      - in: query
        name: DatasetId
        description: 'Unique dataset identifier '
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Datasets
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