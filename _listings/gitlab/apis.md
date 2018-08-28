---
name: GitLab
x-slug: gitlab
description: GitLab is a web-based Git-repository manager with wiki, issue-tracking
  and CI/CD pipelines features, using an open-source license, developed by GitLab
  Inc.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/githlab-logo.png
x-kinRank: "8"
x-alexaRank: ""
tags: Todos
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/todos/master/_listings/gitlab/apis.md
specificationVersion: "0.14"
apis:
- name: API title - Get Todos
  x-api-slug: v3todos-get
  description: Get a todo list
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/githlab-logo.png
  humanURL: http://gitlab.com
  baseURL: https://localhost:3000//api
  tags: Orchestration, Code, Static, Versions, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/todos/master/_listings/gitlab/v3todos-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/todos/master/_listings/gitlab/v3todos-get-openapi.md
- name: API title - Delete Todos
  x-api-slug: v3todos-delete
  description: Mark all todos as done
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/githlab-logo.png
  humanURL: http://gitlab.com
  baseURL: https://localhost:3000//api
  tags: Orchestration, Code, Static, Versions, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/todos/master/_listings/gitlab/v3todos-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/todos/master/_listings/gitlab/v3todos-delete-openapi.md
- name: API title - Delete Todos
  x-api-slug: v3todosid-delete
  description: Mark a todo as done
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/githlab-logo.png
  humanURL: http://gitlab.com
  baseURL: https://localhost:3000//api
  tags: Orchestration, Code, Static, Versions, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/todos/master/_listings/gitlab/v3todosid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/todos/master/_listings/gitlab/v3todosid-delete-openapi.md
x-common:
- type: x-api-gallery
  url: http://github.api.gallery.streamdata.io
- type: x-api-stack
  url: http://gitlab.stack.network
- type: x-documentation
  url: https://docs.gitlab.com/
- type: x-github
  url: https://github.com/gitlab
- type: x-openapi
  url: https://axil.gitlab.io/swaggerapi/static/swagger.json
- type: x-pricing
  url: https://about.gitlab.com/pricing/
- type: x-privacy-policy
  url: https://about.gitlab.com/privacy/
- type: x-support
  url: https://about.gitlab.com/getting-help/
- type: x-terms-of-service
  url: https://about.gitlab.com/terms/
- type: x-twitter
  url: https://twitter.com/gitlab
- type: x-website
  url: http://gitlab.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---