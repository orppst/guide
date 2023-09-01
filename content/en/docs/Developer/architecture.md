---
title: Architecture
date: 2023-11-01
description: >
  The overall architecture of the proposal tool components
categories: [Developer]
tags: [architecture]
---

## Proposal Data Model

The proposal tool uses the [Proposal Data Model](https://ivoa.github.io/ProposalDM/) as
its native storage format. The Proposal Data Model is developed in parallel as it is
intended also to be a stand-alone interchange format that can be used to share proposals between different systems.


## Microservices

The proposal tool is designed as a microservices based architecture
that can run on kubernetes clusters.


```plantuml

skinparam component {
   backgroundColor RosyBrown
}
actor PI
actor "TAC Chair" as tac
[api service] as api
[cli]
[gui service] as gui
[web browser] as web
[aai system] as aai

database "PostgreSQL" as db {
 frame ProposalDM
}
note as keycloak
currently using [[ https://www.keycloak.org keycloak]]
end note

aai .. keycloak

cloud external {
[identity provider] as idp

[simbad]
}

tac --> web
tac --> cli
PI --> web
api -down-> db
gui --> api
aai --> idp
gui --> aai
gui --> simbad
api --> aai
web --> gui
cli --> api

url of cli is [[https://github.com/orppst/pst-cli-app]]
url of gui is [[https://github.com/orppst/pst-gui]]
url of api is [[https://github.com/orppst/pst-api-service]]
url of ProposalDM is [[https://ivoa.github.io/ProposalDM/]]

```




