# Proposal document template for completeness
This template has been created to optimize the completeness of formal proposal docs, based on a "w" question approach of summarization (who/what/when/where).

# What
1. ## What fundamental knowledge is necessary to establish the problem, and potential solutions? (names, terminologies/abbreviations, concepts, technologies, etc.)

1. ## What is the problem this design intends to solve?

    ### a. What is the impact of this problem? (scope/scale/urgency)
    
    ### b. What circumstances prompted the creation of this proposal? (urgency/spare-availability)

1. ## What are the things we need to make sure DO/NOT happen as part of any option? (hard requirements ex: any risk of data loss, or privacy violations)

1. ## What are different scenarios of expected input -> output?

1. ## What are options that could solve the problem?
    ### a. What's the approach? (ex: "I want to use/add/remove/change \<tool/code combination\> to the service [to solve \<the problem\>]")

    ### b. What scenarios does it solve, if not all? (scope of solution)

    ### c. What is effect of the solution on upstream/downstream systems? (load/cascade)

    ### d. What's the risks?

    ### e. What's the resource costs? (money/time/storage/compute/memory/IO/human)

    ### f. What's the proof that the option is viable (PoC)?

    ### g. How novel is the option? (is it complex, has it been done before, is it a hack?)

# When
1. ## When are things that are dependent on this proposal, due? (What does a solution block?)

1. ## When does a solution of this proposal need to be implemented by?

1. ## When are other near-timed happenings which may delay dev/deployment? (ex. code freeze)

# Where

1. ## Where will this be deployed? (which envs)

1. ## Where will artifacts, infrastructure, services, and data live? (account/bucket/cluster/etc)

# Who

1. ## Who is going to be involved ? (probably the implementing-dev, peers for review, and our team in general)

1. ## Who are external upstream/downstream teams affected by this proposal?

    ### a. Do we need to establish/update contracts with them?
        - Will implementation cause an outtage (temporary breach)?
        - Is a breach in contract being fixed with an option?
        - Are we planning on serving more/less to customer, than before?
    ### b. Will we be increasing/decreasing load on their services?

    ### c. Do we need to communicate/coordinate with them during deployment? (point of contact?)

# Follow-up
Use this section to record action items, including researching details that come up during discussion but haven't been prepared (and will be clarified out-of-band)

actionable items:
- schedule followup meeting
- clarify items:
    - uncertain tool/system/dependency capabilities/limits (documentation/suppport/PoC)
    - uncertain hard requirements/contracts (customer/management)
    - uncertain dates (management)
    - uncertain scenarios (input -> output)
- write/execute execution/coordination plan (developer)

# Decision
Use this section to record which option was selected and why (over alternatives)
## Selected option

## Reasoning
