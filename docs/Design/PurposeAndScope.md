
# ***Purpose and scope***

Provide an online web application available over the Internet for astronomers to create observing proposals and submit them to participating observatories. Each observatory’s Time Allocation Committee (TAC) will nominate technical and scientific reviewers to consider each submitted proposal. A review scoring system will determine whether or not the TAC allocate observing time to a submitted  proposal.

The application will be known as the Polaris Proposal Submission Tool (Polaris).

## **Overall scope and goals**

Polaris will manage the following activities:-

* Participating observatories publish their future observing cycles, typically of six months duration. Each observatory maintains an inventory of available resources.

* Astronomers create, maintain, and submit observing proposals for one of those cycles. 

* * Their proposal will include sufficient scientific and technical details for the TAC to be able to make an informed decision about the proposal, but no more. 

* * They may submit their proposals to more than one observatory and may also create another proposal from an existing one, submitting it after editing.

* TAC nominated reviewers discover and read astronomers’ submitted proposals and assign to them a score which will determine whether or not observing time is allocated. The final decision regarding observing time allocation rests with the TAC. In the event of an observing cycle being oversubscribed, the TAC may revoke any allocation.

Polaris will *not* manage the following activities

* Providing full configuration details to enable the observatory equipment to fulfil the observation needs of the proposal

* * These will be provided independently by the astronomer once the TAC have agreed to allocate time and resources to the proposal

* Scheduling of resources at an observatory following allocation of time to a proposal by the TAC

* Managing proposal state beyond completion

* * There are complicated rules around publication accessibility


The desired outcomes are that astronomers are able to make their observations using their nominated observatory’s resources, and that the observatory's resources are used effectively.

## **Stakeholders**

| Stakeholder                       |  Description                                                                                                 |
|-----------------------------------|--------------------------------------------------------------------------------------------------------------|
| Administrator                     | Enables efficient use of facilities and resources                                                            |
| Astronomer                        | Applies to use observatory resources to conduct scientific experiments                                       |
| Reviewer                          | Considers submitted observing proposals as directed by the TAC                                               |
| Time Allocation Committee (TAC)   | Considers submitted observing proposal reviews and determines whether or not to award observing time to them |

## **Scope**

| Topic                                                                                    | MoSCoW                                                                                                              |
|------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------|
| Allocate time for a submitted proposal                                                   | Must  - NB Polaris captures this decision but does not have access to the observatory schedules in order to make it |
| Assign roles to users                                                                    | Must                                                                                                                |
| Automate scheduling of proposals                                                         | Won’t – it does provide the input data for a scheduling tool however.                                               |
| Capture all technical configurations necessary to operate the observatory equipment      | Won't                                                                                                               |
| Capture observatory details, eg location, equipment, availability, observing cycles, etc | Must                                                                                                                |
| Capture published state of a completed proposal                                          | Won't                                                                                                               |
| Capture state of a submitted proposal                                                    | Could                                                                                                               |
| Capture system details, eg users and roles                                               | Must                                                                                                                |
| Clone a proposal                                                                         | Must                                                                                                                |
| Communicate with users                                                                   | Should                                                                                                              |
| Create a proposal                                                                        | Must                                                                                                                |
| Download a document                                                                      | Must                                                                                                                |
| Edit a proposal                                                                          | Must                                                                                                                |
| Export a proposal                                                                        | Must                                                                                                                |
| Import a proposal                                                                        | Must                                                                                                                |
| Open a stored document                                                                   | Must                                                                                                                |
| Reject a submitted proposal                                                              | Must                                                                                                                |
| Review a submitted proposal                                                              | Must                                                                                                                |
| Revoke an allocation                                                                     | Must - NB Polaris captures this decision but does not have access to the observatory schedules in order to make it  |
| Score a submitted proposal                                                               | Must                                                                                                                |
| Search for and view a proposal                                                           | Must                                                                                                                |
| Submit a proposal                                                                        | Must                                                                                                                |
| Upload a document                                                                        | Must                                                                                                                |
| Withdraw a submitted proposal                                                            | Should                                                                                                              |


