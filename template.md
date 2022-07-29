# Outage / Activity Details
This activity is to upgrade

1. What is the purpose of this activity or change?
    - 
2. What will be required to execute this change?
    - 
3. What is the expected end state of the system after this change?
    - 
4. What assumptions, if any, are being made about the state of the system at the time of this change?
    - 

# Impact / Risk Assessment
1. What will happen if this CM doesn't happen?
    - 
2. Why is the scheduled time/day the correct time to complete the CM?
    - 
3. Who will be affected and how were they notified?
    - 
4. What is the customer/user experience for this change while it is in progress?
    - 
6. What public services could be affected?  Is this change modifying a public api, website?  Which one?
    - 
7. What internal services could be affected?  Is this change modifying a internal api, booking platform, anatlics platform?  Which one?
    - 
8. If this CM is an Emergency, please explain why the CM cannot wait until the next CAB to be reviewed
    - 
9. If this CM is Retrospective, please explain why it needed to occur prior to review and approval
    - 
10. What needs to happen before performing this CM?  Are there any related, prerequisite changes upon which this CM hinges?
    - 
11. How will alarming be suppressed during the change (datadog, cloudwatch, etc.)?
    - 
12. Describe your pre-CM test plan. 
    - 

# Worst Case Scenario
(Plan for the worst and hope for the best. Try to keep this realistic. If the server does not reboot, do we have access to the hypervisor, do we need to contact another team. Will BCP's be informed if the change over runs.)

1. What is the realistic worst case scenario in terms of customer impact?
    - 
2. How does this CM attempt to mitigate this risk?
    - 

# Affected Services
1. Does this change involve other teams? Are they aware of this CM and on the communication and/or approvals lists?
    - 
2. Provide links to your RTO/RPO documentation
    - 
3. List hosts and services affected
    - 

# Rollback Procedure
(just provide a general overview here.)

1. What conditions would indicate a need to rollback?
    - 
2. In the event of problems, what will you do to return your system to a known good state?
    - 

# Approval Checklists
All questions answered with [YES|NO|NA]
## Level: 1
1. Is there evidence that rollback procedure has been successfully tested? 
1. If code was developed or modified, was there a code review and is there a link to the code review? 
1. If this CM involves more than an a few lines of commands or clicks that need to be copy-and-pasted, have the configs/scripts been reviewed? 
1. Does this CM call-out how we will know to initiate rollback? 
1. Does this CM define pre tests to ensure the system is in a good state before commencing the change?
1. Do the validation steps include steps to validate that the change actually worked as intended? We shouldn't just check that nothing has broken. 
1. Does this change require Level 2 review?

## Level: 2
1. Has this CM been peer reviewed by an appropriate member of the relevant Team(s)? 
1. Are you confident that this is the right procedure? 
    - Do we know what errors will look like if this CM goes wrong? 
    - Assume that the CM goes wrong, are you confident that all precautions that could have been taken were taken? 
1. Does the CM call out how we will know to initiate rollback? 
1. If different, are mitigation steps called out separately from the rollback procedure? 
1. Are there other major deployments that coincide with this CM? 
    - If yes, should they be serialized (sequenced)?
1. Is this CM being executed by someone with adequate operational experience? 
1. Does this change required CAB review?

## Level: 3 (CAB)
1. Change to be discussed at weekly CAB call