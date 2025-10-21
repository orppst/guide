---
title: Adding Targets
date: 2025-10-21
description: >
   _Guide to adding **Targets** to your proposal_
categories: [Examples]
tags: [test, sample, docs]
---

Last updated: 2025-10-21 Polaris _beta_ version

# Adding a Targets

A fresh proposal will have no **Targets** added, and you will be presented with the following page:

![add a target](polaris-targets-none.png)

# Add a Single Target

To add a single **Target** click the _Add One Target +_ button, which will bring up the _New Target_ form.

!["new target form](polaris-simbad-search-target.png)

In the screenshot you will see we have found the _Crab Nebula_ using the **SIMBAD search** function.
This fills in the corresponding positional and coordinate system data for the named target, and displays 
the target in the [Aladin Lite Sky Atlas](https://aladin.cds.unistra.fr/) (admittedly there more for eye-candy than functional reasons)

Notice that the backend uses [Simbad](https://simbad.cds.unistra.fr/simbad/) to search for the named target, such that the name must 
exist in their databases to be successful; an appropriate error notification is displayed if the 
named target cannot be found. We have provided useful help, hints, and tips to aid in using the search
facility. Notice that the name displayed after selecting a search item is the _main-id_ found in the Simbad 
database. In the screenshot shown the _main-id_ for the Crab Nebula is "M 1".

You may also double-click anywhere on the displayed Sky Atlas. This will centre the Atlas under the
position you just double-clicked and fill out the form with a "random" target name and the corresponding 
positional details will be updated in the RA and DEC fields. These will be displayed as sexagesimal with
the equivalent degree value displayed under the field box. 

You can also manually fill in the fields, the Sky Atlas will automatically change the view to those 
coordinates. Notice that in this beta version of Polaris, you can have any coordinate system you like, 
so long as it's _J2000_ with an ICRS reference system.

You can change the name of the target after you have looked it up and before you save it as a 
**Target**. Be aware that each target must have a unique name within a proposal. To save, click the _Save_ 
button. This will return you to the **Targets** page of your proposal 
now displaying the **Target** you just saved, and any other targets you may have added. Clicking _Cancel_
on the new target form will take you back to the targets list page without saving.

![list of targets](polaris-target-list.png)

You may _Delete_ this **Target** if you so wish, just remember that you need at least one target in order
to build an **Observation** for your proposal. For information, you will not be able to delete **Targets** 
that currently belong to an **Observation** - the corresponding **Observation** must be deleted first.

## Adding Several Targets via File Upload

Instead of adding **Targets** one at a time, we have provided a means to add several **Targets** at once
via a file upload; click the _Upload List of Targets_ button. Compatible files are **VOTable xml** (obtained 
from _Simbad_ or another service), **Astropy generated ecsv**, or manually created txt. We recommend using 
either the VOTable xml or the Astropy generated ecsv but if you are a masochist read on.

The manually created txt file should have the following format:

```
#name,ra,dec,pmra,pmdec,plx,rv
alpha,12.987,34,42,69,,99
beta,56,78,11,13,33,112
gamma,90,-12,38,-34,-1,-86
```

where you are required to provide the columns 'name', 'ra', and 'dec' of the targets, the other
columns may be omitted with the caveat that if you provide one proper-motion ('pm') column, you must provide the
other. The names can only be ASCII characters and the other values are integer or decimal digits. All units are in degrees 
or degrees per second for rates. The order of the columns is not important (to the code at least, 
to your sanity maybe). Any optional data values i.e., 'pmra', 'pmdec', 'plx', 'rv', that isn't available but for which
you have a column should be left blank e.g., the target 'alpha' in the (made-up) list above has no parallax data. Again
we recommend using either one of the other two formats to add a list of targets.

## Next Step

If you haven't already added a **Technical Goal** then please follow the guide [here](adding-technical-goals.md).
If you have now added at least one **Target** and one **Technical Goal** to your proposal then please 
follow the link to [**Building an Observation**](build-observation.md).