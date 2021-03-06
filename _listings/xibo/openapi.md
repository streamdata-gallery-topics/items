swagger: "2.0"
x-collection-name: Xibo
x-complete: 1
info:
  title: Xibo API
  description: xibo-cms-api
  termsOfService: http://xibo.org.uk/legal
  version: 1.0.0
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /displaygroup/{displayGroupId}/media/assign:
    post:
      summary: Assign one or more Media items to a Display Group
      description: Adds the provided Media to the Display Group
      operationId: displayGroupMediaAssign
      x-api-path-slug: displaygroupdisplaygroupidmediaassign-post
      parameters:
      - in: path
        name: displayGroupId
        description: The Display Group to assign to
      - in: formData
        name: mediaId
        description: The Media Ids to assign
      - in: formData
        name: unassignMediaId
        description: Optional array of Media Id to unassign
      responses:
        200:
          description: OK
      tags:
      - Assign
      - More
      - Media
      - Items
      - To
      - Display
      - Group
  /displaygroup/{displayGroupId}/media/unassign:
    post:
      summary: Unassign one or more Media items from a Display Group
      description: Removes the provided from the Display Group
      operationId: displayGroupMediaUnassign
      x-api-path-slug: displaygroupdisplaygroupidmediaunassign-post
      parameters:
      - in: path
        name: displayGroupId
        description: The Display Group to unassign from
      - in: formData
        name: mediaId
        description: The Media Ids to unassign
      responses:
        200:
          description: OK
      tags:
      - Unassign
      - More
      - Media
      - Items
      - From
      - Display
      - Group
  /displaygroup/{displayGroupId}/layout/assign:
    post:
      summary: Assign one or more Layouts items to a Display Group
      description: Adds the provided Layouts to the Display Group
      operationId: displayGroupLayoutsAssign
      x-api-path-slug: displaygroupdisplaygroupidlayoutassign-post
      parameters:
      - in: path
        name: displayGroupId
        description: The Display Group to assign to
      - in: formData
        name: layoutId
        description: The Layouts Ids to assign
      - in: formData
        name: unassignLayoutId
        description: Optional array of Layouts Id to unassign
      responses:
        200:
          description: OK
      tags:
      - Assign
      - More
      - Layouts
      - Items
      - To
      - Display
      - Group
  /displaygroup/{displayGroupId}/layout/unassign:
    post:
      summary: Unassign one or more Layout items from a Display Group
      description: Removes the provided from the Display Group
      operationId: displayGroupLayoutUnassign
      x-api-path-slug: displaygroupdisplaygroupidlayoutunassign-post
      parameters:
      - in: path
        name: displayGroupId
        description: The Display Group to unassign from
      - in: formData
        name: layoutId
        description: The Layout Ids to unassign
      responses:
        200:
          description: OK
      tags:
      - Unassign
      - More
      - Layout
      - Items
      - From
      - Display
      - Group
  /playlist/library/assign/{playlistId}:
    post:
      summary: Assign Library Items
      description: Assign Media from the Library to this Playlist
      operationId: playlistLibraryAssign
      x-api-path-slug: playlistlibraryassignplaylistid-post
      parameters:
      - in: formData
        name: duration
        description: Optional duration for all Media in this assignment to use on
          the Widget
      - in: formData
        name: media
        description: Array of Media IDs to assign
      - in: path
        name: playlistId
        description: The Playlist ID to assign to
      - in: formData
        name: useDuration
        description: Optional flag indicating whether to enable the useDuration field
      responses:
        200:
          description: OK
      tags:
      - Assign
      - Library
      - Items
  /library/usage/{mediaId}:
    get:
      summary: Get Library Item Usage Report
      description: Get the records for the library item usage report
      operationId: libraryUsageReport
      x-api-path-slug: libraryusagemediaid-get
      responses:
        200:
          description: OK
      tags:
      - Library
      - Item
      - Usage
      - Report
  /library/usage/layouts/{mediaId}:
    get:
      summary: Get Library Item Usage Report for Layouts
      description: Get the records for the library item usage report for Layouts
      operationId: libraryUsageLayoutsReport
      x-api-path-slug: libraryusagelayoutsmediaid-get
      responses:
        200:
          description: OK
      tags:
      - Library
      - Item
      - Usage
      - ReportLayouts