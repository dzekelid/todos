---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Assign InboundLead Todos to the owning Negotiators of the property.
  version: 1.0.0
  description: Assign inboundlead todos to the owning negotiators of the property..
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/todo/getall:
    get:
      summary: "Get the list of all ToDo's if no parameter is sent;\r\n<param name=\"filterToDo\">if
        provided will filter by ToDo type</param><param name=\"pageSize\"></param><param
        name=\"pageNumber\"></param>"
      description: "Get the list of all todo's if no parameter is sent;\r\n<param
        name=\"filtertodo\">if provided will filter by todo type</param><param name=\"pagesize\"></param><param
        name=\"pagenumber\"></param>."
      operationId: DefaultToDo_GetAllBypageSizeBypageNumberByfilterToDo.filterCategoryByfilterToDo.toDoTypeByfilterToDo
      x-api-path-slug: apitodogetall-get
      parameters:
      - in: query
        name: filterToDo.branchId
      - in: query
        name: filterToDo.filterCategory
      - in: query
        name: filterToDo.negotiatorIds
      - in: query
        name: filterToDo.toDoType
      - in: query
        name: pageNumber
      - in: query
        name: pageSize
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - List
      - Of
      - ""
      - ToDos
      - If
      - "No"
      - Parameter
      - Is
      - "Sent;\r\n<param"
      - Name=filterToDo>if
      - Provided
      - Will
      - Filter
      - By
      - ToDo
      - Type<
      - Param><param
      - Name=pageSize><
      - Param><param
      - Name=pageNumber><
      - Param>
  /api/todo/getleads:
    get:
      summary: Get the list of all InboundLead ToDo's
      description: Get the list of all inboundlead todo's.
      operationId: DefaultToDo_GetLeadsBybranchIdByexcludeTasks
      x-api-path-slug: apitodogetleads-get
      parameters:
      - in: query
        name: branchId
      - in: query
        name: excludeTasks
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - List
      - Of
      - ""
      - InboundLead
      - ToDos
  /api/todo/assignleadstoowningnegotiators:
    put:
      summary: Assign InboundLead Todos to the owning Negotiators of the property.
      description: Assign inboundlead todos to the owning negotiators of the property..
      operationId: DefaultToDo_AssignLeadsToOwningNegotiatorsBytoDoId
      x-api-path-slug: apitodoassignleadstoowningnegotiators-put
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: toDoId
      responses:
        200:
          description: OK
      tags:
      - Assign
      - InboundLead
      - Todos
      - To
      - Owning
      - Negotiators
      - Of
      - Property
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