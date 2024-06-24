
# ***Components***

###	*Assigns PI*

Polaris assigns the current user as PI for the created proposal

###	*Assigns Reviewer*

Polaris assigns the current user as Reviewer for the submitted proposal

### *Audit activity*

For all database Create, Update, and Delete activity, Polaris writes to the transaction audit log capturing username, datetime stamp, activity (Create, Update, Delete), and an array of table, fieldname, old value, new value, for each field changed.

For import and export activities, Polaris writes to the transaction audit log capturing username, activity, proposal title and key

###	*Discover cycles*

Polaris compares the proposal’s technical goals with available observatory equipment and returns a list of observatories with proposal cycles having submission deadlines in the future, or a message if none found.

###	*Informs*

Polaris delivers a suitable message to the named target.


### *Reviewer search*

Polaris searches for submissions to the Reviewer’s observatory, returning a list made of Title, Summary, and Status, or a message if none found.

###	*Verify Submission*

Polaris reviews the current user’s proposals - see business rule [***Submitting a proposal***](BusinessRules.md#submitting-a-proposal) - and adds any that are ready for submission to the search results list with any observatory cycles, else an empty list is returned with a suitable message.


### *Withdrawal search*

Polaris searches for the Investigator’s proposals with a status of Submitted, returning a list made of Title, Summary, and Status, or a message if none found.

