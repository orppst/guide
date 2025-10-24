---
title: Adding Technical Goals
date: 2025-10-21
description: >
   _Guide to adding **Technical Goals** to your proposal_
categories: [Examples]
tags: [test, sample, docs]
---

Last updated **2025-10-24** Polaris _beta_ version.

# Add a Technical Goal

A fresh proposal will have no **Technical Goals** and you will be presented with the following page:

![no technical goals summary page](polaris-tech-goals-none.png)


To add a **Technical Goal** click the _Add +_ button, which will bring up the _New Technical Goal_ form.

![new technical goals form](polaris-tech-goals-new.png)


The field values can be freely entered but the units are selected via a drop-down menu. These values are what you would 
like the observation to achieve rather than strict requirements. The _Performance Parameters_ are the 
minimum amount of information required to _Save_ a **Technical Goal**. 

**Spectral Windows** are optional but if provided consist of a _start_ and _end_ frequency defining the range
of the EM-spectrum you are interested in, the _resolution_ of that range, a _polarization_ option, and whether the
frequency of the range is a _sky frequency_. The _Spectral point_ of the _Performance Parameters_ should be related
to this range. 

After clicking _Save_ you will be brought back to the technical goals summary page, which should now display your
newly added **Technical Goal**. 


![technical goals summary page](polaris-tech-goals-list.png)

In the screenshot you can see we have filled out the _Performance Parameters_ with some values and their
corresponding units; the values in the screenshot are contrived for this guide.


Unlike **Targets**, you can also _Edit_ and _Copy_ **Technical Goals** as well as _Delete_ them. This allows you 
to change the attributes of an existing **Technical Goal**, or quickly add other **Technical Goals** that may have 
similar _Performance Parameters_ and/or _Spectral Windows_ without having to re-input all the data. If a 
**Technical Goal** currently belongs to an **Observation** then it cannot be deleted, unless the corresponding
**Observation** is deleted first. However, the _Edit_ and _Copy_ functions are still available.

## Next Step

If you haven't already added a **Target** then please follow the guide [here](adding-targets.md).
If you have now added at least one **Target** and one **Technical Goal** to your proposal then please follow the
link to [**Building an Observation**](build-observation.md).