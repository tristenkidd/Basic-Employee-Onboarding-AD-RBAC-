# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
* The problem in this project was related to a fictional company named Northstar Medical Group. Northstar Medical Group delegated their Identity Lifecycle workflow to a third-party MSP. This MSP was mismanaged leading to several problems. The company had no RBAC policy in place, no audit trails, and had many security risks including with HIPAA. Some employees had security access that was not related to their job title elevating these security risks within the company. 

## Solution Overview
* I provided several solutions for Northstar Medical Group by designing a centralized and secure Active Directory environment to support employee onboarding and offboarding. I created a structured organizational unit (OU) hierarchy to organize employees based on departments and roles, making account management and administration more efficient. Security groups were implemented using a flat RBAC model to assign users the appropriate permissions based on their job responsibilities and limit unnecessary access. This helped also reduce the risk for HIPAA violations. These changes will make it easier to securely provision, modify, and disable employee accounts when their employment status or role changes. I was able to simulate a mock ticket where a user was provisioned the incorrect level of access. 

## Video Walkthrough
[Add your video walkthrough link placeholder here. You will record this tomorrow and update this link so visitors can see a live demonstration of your lab environment.]

## Tools Used
* Windows Server
* Active Directory Domain Services
* VirtualBox
* UTM
* RBAC
* GitHub

## Project Timeline
* Day 1: Domain creation and domain controller promotion
* Day 2: Organizational unit and security group design
* Day 3: User provisioning and RBAC implementation
* Day 4: Incident response and resolution (NMG-0047)
* Day 5: Documentation and case study packaging

## Key Accomplishments
* Built NMG.com domain from scratch
* Implemented the RBAC model
* Completed my first incident response

