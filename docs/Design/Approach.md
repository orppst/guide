
# ***Approach***
These business requirements are documented following Alistair Cockburn’s recommendations in Writing Effective Use Cases, Addison-Wesley, 2001.
## Key points
The use cases are well-formed processes and sub-processes with a purpose, a trigger, some inputs, and some outputs.
The happy path is described as numbered steps in the Main Success Scenario, with alternatives and error responses described in
the Extensions. The numbered steps in the Extensions correspond to the MSS steps.

Some use cases (eg, maintaining investigators) and components (eg audit activity) are called by other use cases, (eg, create a proposal, edit a proposal). Such items are declared just once and referenced by name with a bold italic hyperlink. Click the hyperlink to see the detail and then return with the browser back button.

The data models can be found in a [separate project](https://ivoa.github.io/ProposalDM/).

The UI is documented elsewhere.