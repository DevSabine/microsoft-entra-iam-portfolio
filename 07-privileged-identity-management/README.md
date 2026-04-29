# Privileged Identity Management (PIM) Lab (Microsoft Entra ID)

## Objective

Understand how Privileged Identity Management (PIM) controls and monitors access to privileged roles using just-in-time (JIT) access and least privilege principles.

---

## What is Privileged Identity Management?

Privileged Identity Management (PIM) is a Microsoft Entra ID feature that manages elevated access to critical roles.

Instead of assigning permanent administrative privileges, PIM enables:

- Just-in-Time (JIT) role activation
- Time-limited access to privileged roles
- Approval-based access workflows
- Monitoring and auditing of privileged activity

---

## What Problems Does It Solve?

PIM helps protect organizations from:

- Excessive or permanent admin access
- Insider threats
- Compromised privileged accounts
- Lack of visibility into elevated access

It enforces **least privilege access**, ensuring users only have elevated permissions when required.

---

## How PIM is Used

In real-world environments, PIM is used to:

- Require approval before activating admin roles
- Enforce MFA during role activation
- Limit duration of elevated access
- Track and audit all privileged activity

Example workflow:

1. User is assigned as **eligible** for a role
2. User requests activation
3. MFA and/or approval is required
4. Role is activated temporarily
5. Access automatically expires

---

## Implementation Notes

In this lab environment:

- Privileged Identity Management was successfully located
- Microsoft Entra roles were explored
- Role activation (JIT) workflow was accessed
- Role assignments section was identified but restricted

Limitations observed:

- PIM requires **Microsoft Entra ID Premium P2**
- Role assignment and activation features were restricted
- Licensing prevented full configuration

This reflects real-world IAM environments where:

- Privileged access is tightly controlled
- Elevated permissions require additional validation
- Licensing and RBAC determine access capabilities

---

## Skills Demonstrated

- Privileged Access Management (PAM)
- Identity and Access Management (IAM)
- Role-Based Access Control (RBAC)
- Just-in-Time (JIT) access concepts
- Zero Trust security principles

---

## Why It Matters

PIM is critical for securing administrative access in cloud environments.

It allows organizations to:

- Reduce attack surface
- Prevent privilege abuse
- Enforce strong access controls
- Maintain visibility into high-risk roles

PIM knowledge is essential for:

- IAM Analyst roles
- SOC Analyst roles
- Cloud Security positions

---

## Screenshots

### Step 1: PIM Overview
![PIM Overview](01-pim-overview.png)

### Step 2: Entra Roles Page
![Roles Page](02-roles-page.png)

### Step 3: Role Assignments (Restricted)
![Role Assignments](03-role-assignments.png)

### Step 4: License / Permission Message (P2 Required)
![License or Permission Message](04-license-or-permission-message.png)
