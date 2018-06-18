---
name: Microsoft Graph
x-slug: microsoft-graph
description: 'Microsoft Graph exposes multiple APIs from Office 365 and other Microsoft
  cloud services through a single endpoint: https://graph.microsoft.com. Microsoft
  Graph simplifies queries that would otherwise be more complex. You can use Microsoft
  Graph to: Access data from multiple Microsoft cloud services, including Azure Active
  Directory, Exchange Online as part of Office 365, SharePoint, OneDrive, OneNote,
  and Planner. Navigate between entities and relationships. Access intelligence and
  insights from the Microsoft cloud (for commercial users).'
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Fill
created: "2018-06-18"
modified: "2018-06-18"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/fill/master/_listings/microsoft-graph/apis.md
specificationVersion: "0.14"
apis:
- name: Microsoft Graph Range Fill Clear
  x-api-slug: microsoft-graph
  description: 'RangeFill: clear Resets the range background.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/range/format/fill/clear
  tags: Range, Fill, Clear
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fill/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatfillclear-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fill/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatfillclear-post-openapi.md
- name: Microsoft Graph Range Fill Clear
  x-api-slug: microsoft-graph
  description: 'RangeFill: clear Resets the range background.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/fill/clear
  tags: Range, Fill, Clear
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fill/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatfillclear-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fill/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatfillclear-post-openapi.md
- name: Microsoft Graph Range Fill Clear
  x-api-slug: microsoft-graph
  description: 'RangeFill: clear Resets the range background.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format/fill/clear
  tags: Range, Fill, Clear
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fill/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatfillclear-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fill/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatfillclear-post-openapi.md
- name: Microsoft Graph Get Range Fill
  x-api-slug: microsoft-graph
  description: Get RangeFill Retrieve the properties and relationships of rangefill
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/range/format/fill
  tags: Range, Fill
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fill/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatfill-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fill/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatfill-get-openapi.md
- name: Microsoft Graph Get Range Fill
  x-api-slug: microsoft-graph
  description: Get RangeFill Retrieve the properties and relationships of rangefill
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/fill
  tags: Range, Fill
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fill/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatfill-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fill/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatfill-get-openapi.md
- name: Microsoft Graph Get Range Fill
  x-api-slug: microsoft-graph
  description: Get RangeFill Retrieve the properties and relationships of rangefill
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format/fill
  tags: Range, Fill
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fill/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatfill-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fill/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatfill-get-openapi.md
- name: Microsoft Graph Update Rangefill
  x-api-slug: microsoft-graph
  description: Update rangefill Update the properties of rangefill object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/range/format/fill
  tags: Rangefill
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fill/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatfill-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fill/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatfill-patch-openapi.md
- name: Microsoft Graph Update Rangefill
  x-api-slug: microsoft-graph
  description: Update rangefill Update the properties of rangefill object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/fill
  tags: Rangefill
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fill/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatfill-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fill/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatfill-patch-openapi.md
- name: Microsoft Graph Update Rangefill
  x-api-slug: microsoft-graph
  description: Update rangefill Update the properties of rangefill object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format/fill
  tags: Rangefill
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fill/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatfill-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fill/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatfill-patch-openapi.md
- name: Microsoft Graph
  x-api-slug: microsoft-graph
  description: 'Microsoft Graph exposes multiple APIs from Office 365 and other Microsoft
    cloud services through a single endpoint: https://graph.microsoft.com. Microsoft
    Graph simplifies queries that would otherwise be more complex. You can use Microsoft
    Graph to: Access data from multiple Microsoft cloud services, including Azure
    Active Directory, Exchange Online as part of Office 365, SharePoint, OneDrive,
    OneNote, and Planner. Navigate between entities and relationships. Access intelligence
    and insights from the Microsoft cloud (for commercial users).'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Fill
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fill/master/_listings/microsoft-graph/openapi.md
x-common:
- type: x-change-loge
  url: https://developer.microsoft.com/en-us/graph/docs/overview/changelog
- type: x-documentation
  url: https://developer.microsoft.com/en-us/graph/docs
- type: x-explorer
  url: https://developer.microsoft.com/en-us/graph/graph-explorer
- type: x-getting-started
  url: https://developer.microsoft.com/en-us/graph/docs/get-started/rest
- type: x-github
  url: https://github.com/microsoftgraph
- type: x-sdk
  url: https://developer.microsoft.com/en-us/graph/code-samples-and-sdks
- type: x-website
  url: https://developer.microsoft.com/en-us/graph/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---