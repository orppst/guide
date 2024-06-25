# ***Non-functional requirements***

## *Inactivity*

After tba minutes inactivity, Polaris will warn the user that the session will be terminated in tba minutes if there is no further activity, and terminate the session if there is no response within that time.

## *Operations, Security and Deployment*

Who will be responsible for providing these services?

## *Response to System Failure*

What will be in place in the the event of a system failure?

## *Use and Accessibility*

Are there guidelines for these?

## *Performance and Availability*

Are there guidelines for these?

## *Maintenance and Portability*

Are there guidelines for these?

## *Extensibility and Scalability*

Are there guidelines for these?

## *Legal*

Who will be responsible for compliance with The UK GDPR and any local arrangements within Manchester University?

## *Training and Documentation*

How will users be trained?

## *Assumptions and Dependencies*

### *AAI system*

Creates Polaris account for applicant.

AAI does little if any checking, we would like it to check the applicant’s email address and membership of an academic institution.


## *Interfaces to other systems*

Polaris will import proposals in the approved Polaris Exchange Format from any external system 

Polaris will export proposals to any external system in the approved Polaris Exchange Format

## *Volumes*


Here are the usage estimates for the expected lifetime of the PST

discrete users : in 1000s

concurrent users : in 10s (near submission time)

proposals and rate of creation : proposals in 1000s and maybe 100s per day (near submission time)

investigators per proposal : 1-10

observations per proposal : typically only a few if single target - however could be 1000s for surveys

spectral and timing windows per target per proposal : a few

document numbers and volume per proposal : < 10 (documents are intended to be images to be included in the justifications)

required equipment per proposal : 

observatories and organisations taking part : perhaps 10

TACs per observatory : typically only one

equipment and its spectral windows, arrays, and configurations per observatory :

submitted proposals per observatory per cycle : 10s - 1000s

allocated proposals per observatory per cycle :10s-100s


## *Dependencies*

AAI grants access to Polaris to prospective users. We would like it to verify their email address and membership of a recognised academic institution before doing so.

Polaris does not have access to observatory schedules, so revoking an allocation will be a decision made by the TAC who does, but the decision will be captured in Polaris
