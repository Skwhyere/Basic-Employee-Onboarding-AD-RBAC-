# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
Prior to this project, Northstar Medical Group experienced severe identity and access management vulnerabilities stemming from managed service provider (MSP) mismanagement. The existing environment lacked a logical directory structure, leading to inconsistent, error-prone manual onboarding and offboarding workflows. Critical systems suffered from excessive privilege sprawl, where standard staff accounts possessed administrative and cross-departmental access by default. Without enforced access controls or standardized provisioning, sensitive internal systems and records were exposed to unauthorized access, presenting significant compliance and data security risks.

## Solution Overview
To remediate these risks, a secure enterprise Active Directory infrastructure was architected and deployed from the ground up for the newly provisioned domain. A tiered Organizational Unit (OU) hierarchy was designed to enforce clear separation of administrative, departmental, and operational objects. A flat Role-Based Access Control (RBAC) model was implemented using structured Security Groups to align all access with the principle of least privilege. User provisioning workflows were standardized with baseline security configurations, ensuring new accounts receive only verified, role-necessary access upon creation. This architecture eliminated privilege sprawl, secured sensitive company assets, and established an auditable, scalable foundation for identity governance.

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
* Designed a structured OU hierarchy and flat RBAC security group model to enforce least-privilege access
* Standardized secure user provisioning and successfully investigated, remediated, and documented ticket NMG-0047
