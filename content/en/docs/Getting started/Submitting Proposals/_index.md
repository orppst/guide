---
title: Submitting Proposals
date: 2024-03-04
description: >
   _Guide to submitting your **Proposal**_
categories: [Examples]
tags: [test, sample, docs]
---

{{% pageinfo %}}
Please be aware that the submission functionality of Polaris is under active development such that this page
may very well be out-of-date. Please bear with us while we get around to updating this page. 

Last updated **2024-03-06** Polaris _alpha_ version.
{{% /pageinfo %}}


# Submit your Proposal

Once you are happy with the details of your **Proposal**, and it has passed the server side validation checks 
you may submit it for review.

<img src="/images/getting-started/proposal_submission_ready.png" style="width: fit-content" alt="proposal submission ready">
<br />
<br />

You will have to select the **Proposal Cycle** from the drop-down menu to which you wish to submit your **Proposal**.
Once selected the page will display the submission deadline for that cycle.

Server side validation checks currently include:

* the **Proposal** _Title_, _Summary_, and _Kind_ attributes are set (the App prevents you from leaving any of these blank)
* at least one **Observation** added with at least one **Timing Window**
  * which requires at least one **Target** and at least one **Technical Goal**

As we develop the server side validation checks this list will grow. For example, we'd expect that a **Proposal** 
must have a **Scientific Justification** and a **Technical Justification** to be valid for review. Indeed, we 
expect this list to grow as we put Polaris in to beta-testing.

If a **Proposal** doesn't pass the validation checks then you will be presented with the following page for the 
_Submit_ tab of your proposal, which lists the problems.

<img src="/images/getting-started/proposal_submission_not_ready.png" style="width: fit-content" alt="proposal submission not ready">
<br />
<br />

Here we have created another proposal but haven't added any **Targets**, **Technical Goals**, or **Observations**.