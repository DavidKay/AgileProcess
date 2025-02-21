# Definition of Ready

It is important that a workstream has clarity on the items required for the Sprint, so both the Business's and Workstream's expectations are met. The Definition of Ready includes: -

## User stories
A clearly defined user story following the standard format
 
- As a "Type of User" I want "some goal" for "some reason"

- User Stories should follow the INVEST principle where possible

  - Independent of other stories, so they are easier to work with

  - Negotiable, the finer details can be worked out during development

  - Valuable, to the customer so delivery provides something they can use

  - Estimable, this doesn’t have to be exact but enough for scheduling

  - Small, good stories tend to be small and deliverable in a Sprint

  - Testable, ensures the requirements are understood with Acceptance criteria

- Please see [Agile Alliance - Invest](https://www.agilealliance.org/glossary/invest/) & linked articles for more guidance

> [!NOTE]
> This is just a guide and a user story's format is not set in stone. If taken too literally, the following might occur:
> 
> 
> As a business  
> I want the data loaded into the database  
> So that I can see the data in the database  
> 
> 
> Yes that is a real life user story from a fintech in 2017. Try not to do that!


## Technical tasks
These can be raised as subtasks to user stories. The key difference is that the user story deals with the business impact on the actors and behavioural aspects, whereas the technical tasks deal more specifically with technical implementation and testing detail of the ticket. This enables the development team to segregate the principles and not try to force business language into technical acceptance. A GET request returning a 418 response for example.
- These tasks can be split amongst different developers
- Each technical task will have associated acceptance criteria
- Technical tasks are not pointed – the user story that they relate to will encompass the effort of all tasks underneath it
- Stories are only marked as complete when all tasks are marked as complete

## Acceptance criteria
These describe all business rules or conditions which must be met, before the User Story is deemed complete
- In the format Given or When or Then
- Generic validation behaviour and feedback text for user input
- Must include happy and unsuccessful paths, so error conditions are covered
- Forms the basis of Test Cases and future Test Automation cases
Please see Agile Alliance – Acceptance for more information and guidance

## Additional criteria and artefacts
- Any UI/UX design is completed and attached to the User Story

- Follow the principle of the Agile Alliance - The Three Amigos, which means the
 PO/BA, Development and Testing must all agree on the change before proceeding

- A set estimate for the story, which can be delivered within the Sprint
  - i.e. larger goals should be broken down

- Any dependency for resource outside of the Team has been discussed and agreed

- Any dependency on assets or services have been supplied (graphics, APIs,
 hardware, software, certificate etc.)

- Architectural and business diagrams should be present when relevant or helpful
