# Company context and security scope
## 1. Companny Overview
  - **Company name:** AgenciaSEO Marketing Digital
  - **Industry:** Digital marketing
  - **Company size:** 12 employees
  - **Geographical scope:** Spain

The company is a pyme organization with a strong reliance on cloud-based service and remote work. Security operations are handled internally by a 3 employees of differente departments (CEO, Web developing, SEO), without a dedicated SOC (Security Operations Center).

This documentation represents the starting point for stablishing basic security operations.

## 2. Current Security Situation (Initial state)
At the time of writting this documents:
  - No formal security policies exist
  - No documented security procedures are in place
  - No defined security roles or responsabilities
  - No incident response process
  - No regultar access reviews
  - Security controls are partially enabled by default, without governance.

## IT and Organizational context
  - **IT tema size:** 3 employees
      - No SIEM or centralized security logging
      - There i is responsible for infraestructure, users and apps.

## 4. Technology stack
  - **Identity & Access**
      - Microsoft 365
      - Microsoft Entra ID
      - Users created manually
      - Permissions assigned ad-hoc
      - MFA not consistently enforced
  - **Endpoints and devices**
       - Corporate laptops (Windows)
       - Corporate pcs (Windows)
       - AVG Antivirus enabled
       - No formal device compliance process
  - **Applicattions**
      - Microsoft 365
      - Several Saas applications
      - Acces often granted directly to users instead of groups
   
## 5. Security maturity level
**Maturity level:** Initial / Ad-hoc
Characteristics:
  - Security is reactive
  - Controls are not documented
  - Knokledge resides in individuals, not in processes
  - No audit-ready evidence exists

The principal **goal** is create a minimum viable security operations.

## 6. Primary security risks
Bases on the current state, the main risks are:
  - Phishing
  - Excessive iser permissions
  - Former employees about security
  - Lack of visibility during incidents
  - No evidence for audits

Security operations will focus on risk reduction, not risk elimination

## 7. Initial security operations objectives
The first step of security operations aims to:
  - Establish basic identity and access controls
  - Define clear, repeatable procedures
  - Ensuere minimum privilege for users
  - Enable MFA consistenly
  - Create iccident handling guidelines
  - Prepare the organization for audits

This is an **incremental and pragmatic approach**

## 8. Constraints and assumptions
  - Limited security budget
  - No SOC or SIEM
  - Small IT team
  - Business continuity has priority
  - Manual processes are acceptable if documented

## 9. Purpose of this document
This document defines the basline security context.
All procedures, policies, and playbooks in this repository are built on top  of this intial state, assuming that security is being implementd from scratch.

## 10. Document Ownership
  - **Owner:** Luis M. Rodríguez
  - **Status:** Initial Version
  - **Last Review:** 09 feb 2026
