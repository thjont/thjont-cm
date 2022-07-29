# Why?
What are the key goals for a change process?
- A searchable databse of CM's that are in Progress.
- tracking delayes caused by changes being "sent for rework"
- 

# Workflow

Draft > Requesting Approval > Approved > In Progress > Closed
        Sent for Re-Work    <

## Draft
  - any change that has not been sent for aproval
## Requesting Approval
  - All changes require a minimum of L1 approval.
  - The requestor should do their best to judge if a change requres additional L2,  or L2 and L3 approval.
  - If the change has more risk and if the creator has not requested the L1 approver can request that the change is review by a L2 aprovals.
  - If the change has a high risk or large reach and the creator has not already requested it, the L2 approver can request the change is Reviewed at CAB.
## Sent for Re-Work
  - Sending a change for rework is a key indicator for delays in the process
  
## Approved
 - Once all Approvals are completed the change is moved to approved.
## In Progress
  - When the Engineer starts work on the change it is moved to In Progress
  - when they are done it is moved to Closed
## Closed
  - When a change is moved to closed it's closure code is set.

# Closure codes
When a change is closed it's closure code is set.

- Successful
  - The change was moved to closed and was completed as defined in the steps. 
- Seccessful Off Script
  - The change was moved to closed, steps were taken that are not defined in the pre-planned steps
  - Causing an unexpected outage and failing forward, is considred off script.
- Rollback
  - the change failed and was rolled back to a known safe state.

## Should notes be added on Closure?
Notes should be added if the closure code is not Successful. Notes should detail why the change did not follow the intended script or rollback was performed.

# Obglitations

## Requestor
The requestor will fill in the for to the best of their ability and judge the impact of their change, adding L1, L2 and L3 approvals as required.

## Approvers
Each aprover should answer the questions in their section and not waste time on questions asked in the other approval Levels obgliations. If an approver is unable to adequitly answer the questions in their section they should delegate to someone else.

### Level 1
Level 1 approvers are primarilary concerned with the technical aspects of the change and rollback procedures.

### Level 2
Level 2 apporvers are primarilary consered with the business changes and if the correct technical review process has been followed correctly. Have the correct teams been notified? Have BCP's been notififed and coms been sent to customers?
Level 2 approvers should not need look at the technicl detail of the change.

### Level 3 (CAB)
Changes where multiple teams are involved and there may be sugnificent risk the changes are reviewed by the board.

# Out Of Process Changes
If the changes is an emergency and cannot wait for the weekly CAB schedule. In the "Impact / Risk Assessment" section, question 9, the reasons for not following the weekly review schedule should be detailed.

## out of cycle changes
If the changes is an emergency and cannot wait for propper review. In the "Impact / Risk Assessment" section, question 8 the reasons for not following the review process should be detailed.

## Emergency Changes
Emergency changes are most likely made by an engineer when working on a P1 incident. Due to the time senestive nature it may not bo possible to assemble the required approvals before making the change. When filling in Retrospectivly question 9 should detail why it was not possible to complete the chagne.

# Change Advisory Board

## what is the purpose of CAB?
CAB is to ensure that the correct technical process and communications are being followed for high risk and far reaching changes.

## What is CAB not?
Cab is not a platform to communicate that a change is to take place. The change document should already detail who the key stake holders are and any other parties who need to be informed, and how and when they are to be communicated with.

## Who should not attend CAB?
- Business Tech Partners - If required the BTP should already be on the communications list or appear as a L2 reviewer.
- Helpdesk - all information that help desk require should be included in the change document.

If the Helpdesk or BTP have something to contribute to a change at CAB, then the L1 and/or L2 approvals have failed in their task.

## who should attend?
The following attendance is required for CAB to go ahead.

- required
  - The engineer requesting the change (they can leave when finished with their change)
  - at least 1 principal engineer
- Optional
  - The L1 approver of each change to be reviewed
  - the L2 approver of each chagne to be reviewed
  - Anyone else who is interested in a change being presented

## Do I need to attend the full meeting?
The 