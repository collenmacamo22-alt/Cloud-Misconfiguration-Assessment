# Logging Disabled

## Misconfiguration

Cloud audit logging is disabled or improperly configured, preventing security teams from monitoring administrative activity, authentication events, and configuration changes.

Without logging, malicious activity may go undetected for extended periods.

---

## Risk

Security teams lose visibility into attacker actions, making incident detection, investigation, and forensic analysis significantly more difficult.

---

## Business Impact

Possible consequences include:

- Delayed incident detection
- Incomplete forensic investigations
- Regulatory compliance failures
- Increased recovery time
- Reduced incident response effectiveness

---

## Common Causes

- Audit logging disabled to reduce costs.
- Logging never configured after deployment.
- Misconfigured logging services.
- Log retention policies set incorrectly.

---

## Detection

Security teams should:

- Verify that audit logging is enabled.
- Review log retention settings.
- Monitor logging service health.
- Alert when logging is disabled or modified.

---

## Recommended Remediation

- Enable audit logging across all cloud services.
- Configure secure log storage.
- Protect logs from unauthorized modification.
- Regularly verify log integrity.
