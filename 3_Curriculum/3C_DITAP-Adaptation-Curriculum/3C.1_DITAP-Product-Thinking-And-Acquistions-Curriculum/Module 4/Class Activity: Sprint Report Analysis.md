<img width="1224" height="400" alt="Class Activity" src="https://github.com/user-attachments/assets/06b0f13f-653c-4e1f-bae6-8f416a0db18b" />

# Class Activity: Sprint Report Analysis 

**Scenario setup:** Your agency is overseeing development of a digital ESA (Emotional Support Animal) Registry designed to help citizens register their ESAs, verify documentation, and reduce fraud. You’re serving in the role of Product Owner (PO), Contracting Officer’s Representative (COR), or Product Manager (PM), and the vendor is now three months into delivery.

In this activity, you’ll review a series of fictional sprint reports and evaluate what’s happening from a delivery and oversight perspective. Each report reflects a common challenge in agile contracts—missed deliverables, unplanned changes, and signs of team strain.

You’ll work in groups to analyze each sprint, determine who should take action (PO, COR, or CO), and decide how to respond to keep delivery on track and aligned with contract expectations.

## Activity Instructions: 

1. Break into small groups.  
2. Review each of the three sprint reports, one at a time.  
3. For each sprint, discuss and answer the following:  
   * Who should take action (PO, COR, CO)?  
   * What steps should they take in response?  
   * Why is this action important at this point in delivery?  
4. Prepare to share highlights of your discussion during the group debrief.

## Sprint Report #1: Unverified Progress

### Sprint name: Sprint 5 – “Verify me”

**Sprint goals:**

* Implement identity verification screen for healthcare providers  
* Integrate with legacy credential validation API  
* Display confirmation to users after validation

**Summary of work completed:**

* UI for verification screen completed and demoed  
* API integration was planned but delayed due to missing credentials  
* Confirmation screen implemented but lacks error messaging

**Demo notes:**

* Vendor demoed the UI screen, but the API call was mocked, not live  
* PO accepted the ticket based on visual completion  
* Developer noted integration was "90% done" and would wrap next sprint

**Risks and blockers:**

* API access delay cited as external blocker  
* COR was not informed prior to the demo that integration wasn’t functional  
* No documentation updated to reflect the gap

**Discussion questions:**

* Who should take action in this scenario, and why?  
* What steps should be taken to address the misalignment and lack of transparency?  
* Should this sprint be considered successful from a delivery and oversight standpoint?

## Sprint Report #2: The Quiet Rewrite

### Sprint name: Sprint 6 – “Make it accessible”

**Sprint goals:**

* Improve accessibility for screen reader users  
* Rewrite form logic to simplify validation

**Summary of work completed:**

* Accessibility improvements demoed (alt text, labels, keyboard nav)  
* Team also rewrote backend logic for ESA form validation — not planned in sprint backlog  
* PO reviewed accessibility work and approved stories  
* Backend logic changes were not demoed, tested, or documented

**Demo notes:**

* Dev team “squeezed in” extra work, saying it was needed to make the accessibility changes easier  
* COR only found out about the backend change during retrospective

**Risks and blockers:**

* Potential impact on form validation rules, which tie directly to legal compliance  
* No user stories written or acceptance criteria for the backend logic changes

**Discussion questions:**

* Who needs to respond to this issue, and why?  
* What are the risks of “quiet scope creep” like this in digital delivery?  
* What steps should be taken to ensure visibility and compliance?  

## Sprint Report #3: The Burnout Sprint

### Sprint name: Sprint 7 – “Final submission”  

**Sprint goals:**

* Build final “Submit ESA Registration” screen  
* Store submission data in the system  
* Send confirmation email to users and providers

**Summary of work completed:**

* Submit screen built but had critical bugs during demo  
* Database write partially functional; developer notes indicate reliability issues  
* Email feature not started due to illness of lead developer  
* Sprint velocity dropped by 40%

**Demo notes:**

* PO rejected the submit screen pending bug fix  
* Team appears demoralized, citing unclear priorities and excessive backlog pressure

**Risks and blockers:**

* Burnout and lack of backup planning  
* Features not ready for integration testing next sprint  
* No formal plan to address missed work

**Discussion questions:**

* What can the PO and COR do to support the team and the product?  
* When (if at all) should the CO be engaged?  
* How do you distinguish between a short-term disruption and a pattern of delivery risk?
