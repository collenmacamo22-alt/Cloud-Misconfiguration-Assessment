# Overly Permissive IAM Policies

## Misconfiguration

Identity and Access Management (IAM) users, groups, or roles are granted permissions beyond what is required to perform their legitimate business functions.

These excessive permissions increase the potential impact if an account is compromised.

---

## Risk

Compromised accounts with excessive privileges may allow attackers to:

- Access sensitive resources.
- Modify cloud infrastructure.
- Delete critical services.
- Create new privileged accounts.
- Disable security controls.

---

## Business Impact

Possible consequences include:

- Unauthorized access to confidential information.
- Service disruption.
- Data loss.
- Privilege escalation.
- Complete cloud environment compromise.

---

## Common Causes

- Use of wildcard permissions (for example, `*`).
- Assigning AdministratorAccess unnecessarily.
- Failure to review permissions regularly.
- Lack of least privilege implementation.

---

## Detection

Cloud security teams should:

- Review IAM policies regularly.
- Identify accounts with administrative privileges.
- Audit unused permissions.
- Monitor privilege changes.
- Perform periodic access reviews.

---

## Recommended Remediation

- Apply the Principle of Least Privilege.
- Remove unnecessary permissions.
- Use role-based access control (RBAC).
- Conduct regular IAM audits.
- Monitor privileged account activity.
