# Security scope definition

## 1. Purpose of this document

This document defines the scope of th Security Operations within the organization.

It's purpose is to clearly establish:
  - What security is responsaible for
  - What is currently out of scope
  - Where responsabilites start and end
  - What assumptions and limitations exist

## 2. Security scope overview

Sec OP is responsaible for  **foundational security controls** and **operational security activities**, with a focus on **risk reduction, control and audit readiness**.

## 3. In-Scope Areas
### 3.1 Identity & Access Management (Core Scope)

Security Operations is responsible for:

  - User onboarding and offboarding
  - Role and permission management
  - Enforcement of least privilege
  - MFA enablement and maintenance
  - Conditional access (basic policies)
  - Periodic access reviews
  - Management of privileged accounts (operational level)

### 3.2 Security Incident Handling (Operational Level)

Security Operations handles:

  - Account compromise incidents
  - Unauthorized access events
  - Lost or stolen corporate devices
  - Third-party access misuse
  - Initial containment and documentation

Security Operations is not responsible for advanced forensic analysis or threat hunting.

### 3.3 Endpoint & User Security (Baseline)

Security Operations supports:

  - Basic endpoint security posture
  - Verification of device protection status
  - Coordination with IT for remediation
  - User security awareness at an operational level

### 3.4 Compliance & Audit Support

Security Operations provides support for:

  - ISO 27001 audits
  - ENS (Basic / Medium level)
  - GDPR security-related requirements
  - Customer security questionnaires

This includes evidence collection, documentation, and access reviews.

### 3.5 Security Documentation & Procedures

Security Operations owns and maintains:

  - Operational procedures
  - Incident playbooks
  - Security policies (basic level)
  - Access control documentation
  - Audit-related documentation

 ## 4. Out-of-Scope Areas

The following activities are explicitly out of scope for Security Operations at this stage:

  - SOC operations
  - SIEM deployment or management
  - 24/7 security monitoring
  - Threat hunting
  - Malware analysis
  - Red team / blue team exercises
  - Advanced incident response and forensics
  - Penetration testing

These activities may be considered in future maturity phases.

## 5. Roles & Responsibilities (High-Level)
Security Operations

  - Defines and enforces security procedures
  - Manages identities and access
  - Handles operational security incidents
  - Provides audit evidence
  - Advises IT on security controls

IT Department

  - Manages infrastructure and systems
  - Implements technical changes
  - Supports remediation actions
  - Maintains availability and performance

Management

  - Approves security policies
  - Accepts residual risk
  - Supports security initiatives

## 6. Escalation Boundaries

Security Operations will escalate incidents when:

  - Business impact is high
  - Legal or regulatory risk exists
  - Advanced technical investigation is required
  - External stakeholders are involved

Escalation targets may include:

  - IT Management
  - Legal / Compliance
  - External security providers

## 7. Constraints & Limitations

  - No SOC or SIEM in place
  - Limited security budget
  - Small IT team
  - Manual processes accepted
  - Security must not disrupt business operations

Controls are selected based on practical effectiveness, not theoretical completeness.

## 8. Scope Review & Evolution

This scope is expected to evolve as:

  - Security maturity increases
  - Business size changes
  - Regulatory requirements expand
  - New technologies are introduced

Scope reviews will be performed periodically or after significant changes.

## 9. Relationship to Other Documents

This document works in conjunction with:

  - company-context.md
  - Security procedures and playbooks
  - Security policies
  - Audit evidence documentation

All operational security documentation assumes this scope definition.
