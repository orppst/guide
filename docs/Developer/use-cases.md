---
title: Use cases
date: 2023-11-01
description: >
  The main use cases for the tools
categories: [Developer]
tags: [usecase]
---

The following are the actors and high level use cases for the proposal tool.

```plantuml
left to right direction
title High Level use cases for the Proposal Tool
actor :System Administrator: as sysadmin
actor :AAI User: as user
actor :Observatory Admin: as obsadmin
actor :TAC member: as tacmem
actor :TAC Chair: as tacchair
actor :Reviewer: as rev
actor :CO I : as coi
actor :Principal Investigator: as pi
usecase "deploy the system" as UC0
usecase "user registers to system" as UC1
usecase  "create observatory admin" as UC2
usecase  "configure observatory" as UC3
usecase "create new proposal cycle" as UC4
usecase "create observing proposal" as UC5
usecase "edit observing proposal" as UC6
usecase "submit a proposal" as UC7
usecase "create TAC Chair" as UC8
usecase "add TAC members" as UC9
usecase "review proposals" as UC10
usecase "score proposals" as UC11
usecase "assign observing time" as UC12
usecase "inform PIs about allocation" as UC13
usecase "export whole proposal" as UC14
usecase "import whole proposal" as UC15
sysadmin --> UC0
sysadmin --> UC2
user --> UC1
obsadmin --> UC3
obsadmin --> UC4
user ..>pi
user ..>coi
user ..>tacmem
user ..>obsadmin
tacmem ..>rev
tacmem ..>tacchair
pi-->UC5
coi-->UC6
pi-->UC6
pi-->UC7
pi-->UC14
pi--> UC15
obsadmin-->UC8
tacchair-->UC9
tacchair-->UC10
tacchair-->UC12
tacchair-->UC13
rev-->UC10
rev-->UC11
```

## Digging down

The following use cases occur in rough chronological order of configuring and using the Proposal tool.

### deploy the system

In deploying the system a special user that is the system administrator is created - this user's authentication is managed locally
rather than using the AAI and has full access to the system.

### user registers to system
All other users should go through the AAI mechanisms on initial creation

### create observatory admin
the system administrator configures initial supported observatory object(s) and assigns an already registered user (or users)
to be the observatory administrators

### configure observatory

observatory administrators have the permission to be able to more fully configure observatories - e.g. add telescopes and instruments

### create TAC Chair

the observatory administrators can assign someone to be the time allocation committee chair for the observatory

### create new proposal cycle

The TAC  chair would then create Proposal Cycle

### create observing proposal

A PI will create an observing proposal and invite CO-Is

### edit observing proposal

PIs and CO-Is can edit an observing proposal


### submit a proposal

When the proposal is complete the PI can formally submit the proposal



### add TAC members

The TAC Chair can add existing users to the TAC

### review proposals

The proposals can be distributed to the TAC - this might

### score proposals

There might be a scoring system that allows people outside the TAC to score as well.

### assign observing time

The TAC assigns observing time to the highest scoring proposals

### inform PIs about allocation
### export whole proposal

the proposal could be exported in several forms

### import whole proposal




