---
swagger: "2.0"
x-collection-name: Predix
x-complete: 0
info:
  title: Predix Dynamic Mapping Delete a collection
  description: |-
    Delete the asset collection specified by the collection name. Any associated asset and asset location data
    are also deleted
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/collections/{collectionName}:
    get:
      summary: Return all asset ids for a collection
      description: |-
        Returns the collection name and a list of ids of the assets that belong to
        the collection.
      operationId: returns-the-collection-name-and-a-list-of-ids-of-the-assets-that-belong-tothe-collection
      x-api-path-slug: v1collectionscollectionname-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: Successful response
      tags:
      - Return
      - ""
      - Asset
      - Idsa
      - Collection
    delete:
      summary: Delete a collection
      description: |-
        Delete the asset collection specified by the collection name. Any associated asset and asset location data
        are also deleted
      operationId: delete-the-asset-collection-specified-by-the-collection-name-any-associated-asset-and-asset-location
      x-api-path-slug: v1collectionscollectionname-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: Successful response
      tags:
      - Collection
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