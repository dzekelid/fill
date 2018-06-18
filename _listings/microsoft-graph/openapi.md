---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 1
info:
  title: Microsoft Graph API
  description: microsoft-graph-exposes-multiple-apis-from-office-365-and-other-microsoft-cloud-services-through-a-single-endpoint-httpsgraph-microsoft-com--microsoft-graph-simplifies-queries-that-would-otherwise-be-more-complex-
  version: 1.0.0
host: graph.microsoft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /workbook/names(&lt;name&gt;)/range/format/fill/clear:
    post:
      summary: Range Fill Clear
      description: 'RangeFill: clear Resets the range background.'
      operationId: RangeFill:Clear
      x-api-path-slug: workbooknamesltnamegtrangeformatfillclear-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Fill
      - Clear
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/fill/clear:
    post:
      summary: Range Fill Clear
      description: 'RangeFill: clear Resets the range background.'
      operationId: RangeFill:Clear
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtformatfillclear-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Fill
      - Clear
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format/fill/clear:
    post:
      summary: Range Fill Clear
      description: 'RangeFill: clear Resets the range background.'
      operationId: RangeFill:Clear
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeformatfillclear-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Fill
      - Clear
  /workbook/names(&lt;name&gt;)/range/format/fill:
    get:
      summary: Get Range Fill
      description: Get RangeFill Retrieve the properties and relationships of rangefill
        object.
      operationId: GetRangeFill
      x-api-path-slug: workbooknamesltnamegtrangeformatfill-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Fill
    patch:
      summary: Update Rangefill
      description: Update rangefill Update the properties of rangefill object.
      operationId: UpdateRangefill
      x-api-path-slug: workbooknamesltnamegtrangeformatfill-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Rangefill
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/fill:
    get:
      summary: Get Range Fill
      description: Get RangeFill Retrieve the properties and relationships of rangefill
        object.
      operationId: GetRangeFill
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtformatfill-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Fill
    patch:
      summary: Update Rangefill
      description: Update rangefill Update the properties of rangefill object.
      operationId: UpdateRangefill
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtformatfill-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Rangefill
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format/fill:
    get:
      summary: Get Range Fill
      description: Get RangeFill Retrieve the properties and relationships of rangefill
        object.
      operationId: GetRangeFill
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeformatfill-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Fill
    patch:
      summary: Update Rangefill
      description: Update rangefill Update the properties of rangefill object.
      operationId: UpdateRangefill
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeformatfill-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Rangefill
---