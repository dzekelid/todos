---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 1
info:
  title: Dezrez.Rezi.Client.Api
  version: 1.0.0
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
  /api/todo/assignleadstopredefinedteams:
    put:
      summary: Assign InboundLead Todos to the predefined neg teams. e.g. Sales Valuers,
        Sales Viewings, Lettings Viewings etc etc
      description: Assign inboundlead todos to the predefined neg teams. e.g. sales
        valuers, sales viewings, lettings viewings etc etc.
      operationId: DefaultToDo_AssignLeadsToPredefinedTeamsBytoDoId
      x-api-path-slug: apitodoassignleadstopredefinedteams-put
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
      - Predefined
      - Neg
      - Teams
      - ""
      - E
      - G
      - ""
      - Sales
      - Valuers
      - ""
      - Sales
      - Viewings
      - ""
      - Lettings
      - Viewings
      - Etc
      - Etc
  /api/todo/assignleadsforspecifiednegs:
    put:
      summary: Assign InboundLead Todos to all the specified Negs using round-robin
        assignement.
      description: Assign inboundlead todos to all the specified negs using round-robin
        assignement..
      operationId: DefaultToDo_AssignLeadsForSpecifiedNegsByassignPropertyLeadsCommandDataContract
      x-api-path-slug: apitodoassignleadsforspecifiednegs-put
      parameters:
      - in: body
        name: assignPropertyLeadsCommandDataContract
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Assign
      - InboundLead
      - Todos
      - To
      - ""
      - Specified
      - Negs
      - Using
      - Round-robin
      - Assignement
  /api/list/todos:
    post:
      summary: Get list of todos
      description: Get list of todos.
      operationId: List_TodosByfilterBypageSizeBypageNumber
      x-api-path-slug: apilisttodos-post
      parameters:
      - in: body
        name: filter
        schema:
          $ref: '#/definitions/holder'
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
      - Todos
  /api/list/todotasks:
    post:
      summary: Get list of todos tasks.
      description: Get list of todos tasks..
      operationId: List_TodoTasksByfilterBypageSizeBypageNumber
      x-api-path-slug: apilisttodotasks-post
      parameters:
      - in: body
        name: filter
        schema:
          $ref: '#/definitions/holder'
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
      - Todos
      - Tasks
  /api/list/todotasks/filters/{id}:
    delete:
      summary: Marks Todos task List Filter as deleted
      description: Marks todos task list filter as deleted.
      operationId: List_DeleteTodoTaskListFilterByid
      x-api-path-slug: apilisttodotasksfiltersid-delete
      parameters:
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Marks
      - Todos
      - Task
      - List
      - Filter
      - As
      - Deleted
  /api/todo/canceltodo:
    put:
      summary: Cancel a to-do list from the tile overview of to-dos
      description: Cancel a to-do list from the tile overview of to-dos.
      operationId: DefaultToDo_CancelTodoBycancelTodoCommandData
      x-api-path-slug: apitodocanceltodo-put
      parameters:
      - in: body
        name: cancelTodoCommandData
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Cancel
      - To-do
      - List
      - From
      - Tile
      - Overview
      - Of
      - To-dos
  /api/todo/canceltasks:
    put:
      summary: Cancel a single or multiple tasks from a to-do bucket
      description: Cancel a single or multiple tasks from a to-do bucket.
      operationId: DefaultToDo_CancelTasksBycancelTasksCommandData
      x-api-path-slug: apitodocanceltasks-put
      parameters:
      - in: body
        name: cancelTasksCommandData
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Cancel
      - Single
      - Multiple
      - Tasks
      - From
      - To-do
      - Bucket
---