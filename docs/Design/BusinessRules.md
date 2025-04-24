# ***Business rules***


### *Creating a proposal*

<ul><li>
A proposal cannot be saved unless both the Title and the Summary are not empty.
</li></ul>

### *Document exchange format*

<ul><li>A proposal must be Exported in both PDF format and the approved Polaris Exchange Format (defined elsewhere)</li></ul>
<ul><li>An Imported proposal created in an external system must be presented in the approved Polaris Exchange Format</li></ul>

###	*Editing a proposal*

<ul><li>
A proposal cannot be edited or deleted by anyone other than its investigators.
</li><li>A proposal with a status other than Created cannot be edited or deleted by anybody.
</li><li>Only an Investigator can upload a document to a proposal
</li></ul>


### *Home page features*

<ul><li>
Polaris must not offer the Maintain Polaris observatory reference data option to any user who does not have an Observatory Administrator role, apart from a System Administrator who must create the initial Observatory record and assign an Observatory Administrator to it.
</li><li>Polaris must not offer the Maintain Polaris system reference data option to any user who does not have a System Administrator role.
</li></ul>

### *Observations*

<ul><li>A proposal has one or more observations</li>
<li>An observation has one or more targets, but usually just one</li>
<li>A target is an attribute of one or more observations, and one or more proposals</li>
<li>A target has one set of performance parameters, one or many spectral windows, one or many timing windows, and zero, one, or many constraints, and must be identified as either Observation or Calibration</li>
<li>Performance parameters and spectral windows are known collectively as technical goals, usually just one per target, and maybe even per proposal</li>
</ul>

###	*Proposal cycle*

<ul><li>
Start date must be later than submission deadline, end date must be later than start date.
</li></ul>

###	*Proposal status*

A proposal is assigned one of the following depending on its current state.

<ul>
<li>Allocated: A proposal has been allocated observing time by the TAC
</li><li>Completed: A proposal's observations have all been made
</li><li>Created:   A new proposal is being prepared for submission
</li><li>Rejected:  A proposal has been rejected by the TAC
</li><li>Revoked:   A proposal allocation has been revoked by the TAC
</li><li>Scored:    A proposal has been assigned a score by the TAC
</li><li>Submitted: A proposal has been submitted
</li><li>Withdrawn: A submitted or allocated proposal has been withdrawn by the Principal Investigator
</li></ul>

###	*Reference data*

<ul><li>
Reference data records (People, Organizations, etc) must not be deleted, they must simply be marked as Discontinued.
</li><li>Administrators must never be deleted, they must simply be marked as Discontinued.
</li><li>Do not display discontinued records when offering a selection.
</li><li>Only Administrators can add or change reference data
</li></ul>


###	*Reviewing a proposal*

<ul><li>
A proposal cannot be reviewed by any Polaris-user who is not a nominated Reviewer for the proposal’s chosen observatory.
</li><li>A proposal cannot be reviewed by a TAC member who is also an investigator on the Proposal
</li><li>Investigators’ names must not be displayed to a Reviewer
</li><li>Reviewers’ names must not be displayed to an Investigator
</li></ul>


###	*Revoking an allocation*

<ul><li>
A proposal with a status other than Allocated cannot be revoked.
</li><li>Nobody other than the TAC Chair can revoke a proposal.
</li></ul>


###	*Submitting a proposal*

<ul><li>
A proposal cannot be submitted unless Title, Summary, Justifications, Observations and each of their components (Targets, Technical Goals, Spectral Windows and Timing Windows) all have non-null values.
</li><li>Nobody other than the Principal Investigator can submit a proposal.
</li><li>A proposal with a status other than Created cannot be submitted.
</li><li>A Proposal cannot be submitted to a proposal cycle whose submission deadline is in the past
</li></ul>


###	*Viewing a proposal*

<ul>
<li>A proposal cannot be viewed by anyone who is not one of its investigators or reviewers
</li></ul>


###	*Withdrawing a proposal*

<ul><li>

Nobody other than the Principal Investigator can withdraw a submitted a proposal.
</li><li>A proposal with a status of Completed cannot be withdrawn.
</li></ul>


