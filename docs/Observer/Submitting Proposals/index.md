
Last updated **2025-10-24** Polaris _beta_ version.

# Submit your Proposal

Once you are happy with the details of your **Proposal**, and it has passed the server side validation checks
you may submit it for review. Please notice that submission it restricted to the _Principal Investigator_ only,
_Co-Investigators_ cannot submit proposals.

The proposal submission process consists of several steps.

## Step 1 - Select the **Proposal Cycle**

![proposal submission step 1](polaris-submit-step-1.png)


Here you select the **Proposal Cycle** from the drop-down menu to which you wish to submit your **Proposal**.
Once selected click _Next step_ to continue to the next step.

## Step 2 - Validation Check

Server side validation checks currently include:

* at least one **Observation** added
    * which requires at least one **Target** and at least one **Technical Goal**
* a successfully compiled **Justification PDF**
    * which includes having non-empty **Justification** texts

You _can_ compile an "empty" **Justification PDF** i.e., empty texts, but this will fail the validation check.
Notice that if your justifications texts are short (< 256 characters) then this check will emit a warning to
that effect, as your justification texts should be longer, but it will not fail the check.

As we develop the server side validation checks we expect this list to potentially expand.

If a **Proposal** doesn't pass the validation checks then you will be presented with the following page for 
_Step 2_ in the submission process, which lists the problems.

![proposal submission not ready](polaris-submit-step-2-validation-fail.png)


Here we have created another proposal but haven't added any **Targets**, **Technical Goals**, or **Observations**. 
We also have not written any Justification texts or attempted to compile the PDF document.
Please notice that the messages are links that will take you to the relevant page in Polaris so you can address
the issues. In this case the _Next step_ button is disabled.

A **Proposal** that does pass these validation checks will be shown the following page.

![proposal submission ready](polaris-submit-step-2.png)


Again click _Next step_ to continue to step 3.

## Step 3 - Select **Observing Modes** for your **Observations**

![proposal submission select modes](polaris-submit-step-3.png)


Here you select the **Observing Modes** you want for your **Observations**. Notice that the selectable data here
depends on your choice of **Proposal Cycle**. For example, having chosen the eMerlin proposal cycle (generally 
named "Cycle N", where N represents the cycle number) you can choose between _L-Band_, _C-Band_, and _K-Band_ 
**Observing Modes**. You may either select a single **Observing Mode** for all the **Observations** in your 
proposal, most conveniently done by selecting the mode in the _Observing Mode Details_ section and clicking
the _Set for all_ button, or select the mode for each observation separately. Once each of your **Observations**
has a mode you may proceed to step 4.

The "eye" button in the _Observing Mode Details_ section will toggle a display of the details of the selected mode. 
For example, the eMerlin modes show details of the receivers and the correlator involved, and will show which 
of the telescopes will be used for the observation in the ideal case.

## Step 4 - Review selections before submitting

![proposal submission review choices](polaris-submit-step-4.png)


This is your last chance to ensure all the details selected are correct for your proposal before you submit it 
to the chosen **Proposal Cycle**. If you do need to change something then you may go _Back_ and make the desired 
changes.

Once you are happy with all the details you can click on the _Submit proposal_ button, and all being well, you
should be presented with the following screen.

![proposal submission complete](polaris-sumbit-step-final.png)


You will also be sent a confirmation email outlining that you have just successfully submitted your proposal to
the cycle of choice. This email is sent to all investigators associated with the proposal.

For your information, when your **Observing Proposal** is submitted it is copied into a new **Submitted Proposal**,
in essence creating a "snapshot" of your proposal at the point of submission. The **Submitted Proposal** is a
different entity to your **Observing Proposal** and is non-editable. You may continue to edit your
**Observing Proposal** without effecting the **Submitted Proposal**. If you need to update a **Submitted Proposal**
then you must first withdraw that proposal from the cycle 
(see [**Withdrawing a Submitted Proposal**](#withdrawing-a-submitted-proposal))
and resubmit your edited **Observing Proposal**. 

Clicking on _Done_ will take you back to the _Overview_ page for the proposal.


## Withdrawing a Submitted Proposal

The Principal Investigator may withdraw a submitted proposal from a **Proposal Cycle** up to the submission
deadline for that cycle. The _withdraw_ button is located on the user's homepage, one per cycle to which a proposal 
has been submitted, shown in the screenshot below.

![polaris homepage withdraw](polaris-home-page-withdraw.png)

You may submit and withdraw a proposal to a particular cycle _ad nauseam_, but do try to not over do it, for your 
own sake as much as anyone else's. 
