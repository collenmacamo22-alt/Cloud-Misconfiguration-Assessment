# Remediation – Publicly Accessible Cloud Storage

## Objective

Provide practical recommendations to eliminate unnecessary public access to cloud storage resources and reduce the risk of unauthorized data exposure.

---

## Immediate Actions

- Disable public access to the affected storage bucket or container.
- Verify that sensitive data is no longer publicly accessible.
- Identify all users and applications that require legitimate access.

---

## Access Control

- Apply the Principle of Least Privilege.
- Restrict access using Identity and Access Management (IAM) roles and policies.
- Remove overly permissive permissions and Access Control Lists (ACLs).
- Grant access only to authorized users and services.

---

## Data Protection

- Enable encryption for data at rest.
- Enable encryption for data in transit.
- Review stored data for sensitive information.
- Remove or archive unnecessary files.

---

## Monitoring

- Enable cloud audit logging (e.g., AWS CloudTrail, Azure Activity Logs, or Google Cloud Audit Logs).
- Monitor configuration changes.
- Configure alerts for public access changes.
- Perform regular cloud security reviews.

---

## Long-Term Recommendations

- Implement Infrastructure as Code (IaC) security reviews.
- Conduct periodic cloud security assessments.
- Train administrators on secure cloud configuration.
- Integrate cloud posture management tools into the security program.
