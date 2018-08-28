---
name: Dezrez
x-slug: dezrez
description: Cloud based estate agent software , sales & letting agent software, estate
  agent website design and property management software - Dezrez  Services
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
x-kinRank: "7"
x-alexaRank: "385559"
tags: Todos
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/todos/master/_listings/dezrez/apis.md
specificationVersion: "0.14"
apis:
- name: "Dezrez.Rezi.Client.Api - Get the list of all ToDo's if no parameter is sent;\r\n<param
    name=\"filterToDo\">if provided will filter by ToDo type</param><param name=\"pageSize\"></param><param
    name=\"pageNumber\"></param>"
  x-api-slug: apitodogetall-get
  description: "Get the list of all todo's if no parameter is sent;\r\n<param name=\"filtertodo\">if
    provided will filter by todo type</param><param name=\"pagesize\"></param><param
    name=\"pagenumber\"></param>."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/todos/master/_listings/dezrez/apitodogetall-get-openapi.md
- name: Dezrez.Rezi.Client.Api - Get the list of all InboundLead ToDo's
  x-api-slug: apitodogetleads-get
  description: Get the list of all inboundlead todo's.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/todos/master/_listings/dezrez/apitodogetleads-get-openapi.md
- name: Dezrez.Rezi.Client.Api - Assign InboundLead Todos to the owning Negotiators
    of the property.
  x-api-slug: apitodoassignleadstoowningnegotiators-put
  description: Assign inboundlead todos to the owning negotiators of the property..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/todos/master/_listings/dezrez/apitodoassignleadstoowningnegotiators-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/todos/master/_listings/dezrez/apitodoassignleadstoowningnegotiators-put-openapi.md
- name: Dezrez.Rezi.Client.Api - Assign InboundLead Todos to the predefined neg teams.
    e.g. Sales Valuers, Sales Viewings, Lettings Viewings etc etc
  x-api-slug: apitodoassignleadstopredefinedteams-put
  description: Assign inboundlead todos to the predefined neg teams. e.g. sales valuers,
    sales viewings, lettings viewings etc etc.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/todos/master/_listings/dezrez/apitodoassignleadstopredefinedteams-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/todos/master/_listings/dezrez/apitodoassignleadstopredefinedteams-put-openapi.md
- name: Dezrez.Rezi.Client.Api - Assign InboundLead Todos to all the specified Negs
    using round-robin assignement.
  x-api-slug: apitodoassignleadsforspecifiednegs-put
  description: Assign inboundlead todos to all the specified negs using round-robin
    assignement..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/todos/master/_listings/dezrez/apitodoassignleadsforspecifiednegs-put-openapi.md
- name: Dezrez.Rezi.Client.Api - Get list of todos
  x-api-slug: apilisttodos-post
  description: Get list of todos.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/todos/master/_listings/dezrez/apilisttodos-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Get list of todos tasks.
  x-api-slug: apilisttodotasks-post
  description: Get list of todos tasks..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/todos/master/_listings/dezrez/apilisttodotasks-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Marks Todos task List Filter as deleted
  x-api-slug: apilisttodotasksfiltersid-delete
  description: Marks todos task list filter as deleted.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/todos/master/_listings/dezrez/apilisttodotasksfiltersid-delete-openapi.md
- name: Dezrez.Rezi.Client.Api - Cancel a to-do list from the tile overview of to-dos
  x-api-slug: apitodocanceltodo-put
  description: Cancel a to-do list from the tile overview of to-dos.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/todos/master/_listings/dezrez/apitodocanceltodo-put-openapi.md
- name: Dezrez.Rezi.Client.Api - Cancel a single or multiple tasks from a to-do bucket
  x-api-slug: apitodocanceltasks-put
  description: Cancel a single or multiple tasks from a to-do bucket.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/todos/master/_listings/dezrez/apitodocanceltasks-put-openapi.md
- name: Dezrez.Rezi.Client.Api - Cancel a to-do list from the tile overview of to-dos
  x-api-slug: apitodocanceltodo-put
  description: Cancel a to-do list from the tile overview of to-dos.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/todos/master/_listings/dezrez/apitodocanceltodo-put-openapi.md
- name: Dezrez.Rezi.Client.Api - Cancel a to-do list from the tile overview of to-dos
  x-api-slug: apitodocanceltodo-put
  description: Cancel a to-do list from the tile overview of to-dos.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/todos/master/_listings/dezrez/apitodocanceltodo-put-openapi.md
- name: Dezrez.Rezi.Client.Api - Cancel a single or multiple tasks from a to-do bucket
  x-api-slug: apitodocanceltasks-put
  description: Cancel a single or multiple tasks from a to-do bucket.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/todos/master/_listings/dezrez/apitodocanceltasks-put-openapi.md
- name: Dezrez.Rezi.Client.Api - Cancel a to-do list from the tile overview of to-dos
  x-api-slug: apitodocanceltodo-put
  description: Cancel a to-do list from the tile overview of to-dos.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/todos/master/_listings/dezrez/apitodocanceltodo-put-openapi.md
- name: Dezrez.Rezi.Client.Api - Cancel a single or multiple tasks from a to-do bucket
  x-api-slug: apitodocanceltasks-put
  description: Cancel a single or multiple tasks from a to-do bucket.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/todos/master/_listings/dezrez/apitodocanceltasks-put-openapi.md
- name: Dezrez.Rezi.Client.Api - Cancel a to-do list from the tile overview of to-dos
  x-api-slug: apitodocanceltodo-put
  description: Cancel a to-do list from the tile overview of to-dos.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/todos/master/_listings/dezrez/apitodocanceltodo-put-openapi.md
- name: Dezrez.Rezi.Client.Api - Cancel a to-do list from the tile overview of to-dos
  x-api-slug: apitodocanceltodo-put
  description: Cancel a to-do list from the tile overview of to-dos.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/todos/master/_listings/dezrez/apitodocanceltodo-put-openapi.md
x-common:
- type: x-github
  url: https://github.com/dezrez
- type: x-openapi
  url: https://api.dezrez.com:443/swagger/docs/v1
- type: x-api-gallery
  url: http://datumbox.api.gallery.streamdata.io
- type: x-api-stack
  url: http://dezrez.stack.network
- type: x-documentation
  url: https://api.dezrez.com/swagger/ui/index#!/AccountingExport
- type: x-support
  url: https://www.dezrez.com/uk/estate-agency-software-support
- type: x-twitter
  url: https://twitter.com/dezrezsoftware
- type: x-website
  url: https://www.dezrez.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---