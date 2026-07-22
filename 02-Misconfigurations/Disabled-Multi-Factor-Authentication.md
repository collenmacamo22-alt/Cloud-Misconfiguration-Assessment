# Disabled Multi-Factor Authentication (MFA)

## Misconfiguration

Cloud accounts are protected only by a username and password without requiring Multi-Factor Authentication (MFA).

This significantly increases the likelihood of unauthorized access if user credentials are stolen, guessed, or reused.

---

## Risk

Without MFA, compromised credentials may allow attackers to access cloud resources without additional verification.

---

## Business Impact

Possible consequences include:

- Unauthorized account access
- Data breaches
- Privilege escalation
- Service disruption
- Financial loss

---

## Common Causes

- MFA not enabled for administrator accounts.
- Users not enrolled in MFA.
- Weak organizational security policies.
- Legacy accounts excluded from MFA requirements.

---

## Detection

Security teams should:

- Identify accounts without MFA enabled.
- Audit administrator accounts regularly.
- Review authentication reports.
- Monitor failed and successful login patterns.

---

## Recommended Remediation

- Require MFA for all users.
- Enforce MFA for privileged accounts.
- Remove exceptions unless formally approved.
- Regularly review MFA enrollment.
