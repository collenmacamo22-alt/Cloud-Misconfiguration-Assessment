# Misconfigured Security Groups

## Misconfiguration

Cloud security groups or firewall rules allow unrestricted inbound or outbound network traffic.

Examples include exposing management services such as SSH (22) or RDP (3389) directly to the Internet.

---

## Risk

Attackers may discover exposed services through Internet scanning and attempt unauthorized access using stolen credentials, brute-force attacks, or software vulnerabilities.

---

## Business Impact

Possible consequences include:

- Unauthorized remote access
- Data theft
- Malware deployment
- Ransomware attacks
- Lateral movement

---

## Common Causes

- Allowing inbound access from 0.0.0.0/0.
- Temporary firewall rules left enabled.
- Poor network segmentation.
- Failure to review firewall configurations.

---

## Detection

Security teams should:

- Review security group rules regularly.
- Identify Internet-exposed management ports.
- Monitor firewall configuration changes.
- Perform continuous cloud posture assessments.

---

## Recommended Remediation

- Restrict management access to trusted IP ranges.
- Remove unnecessary firewall rules.
- Apply network segmentation.
- Conduct periodic firewall reviews.
