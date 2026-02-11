# MedTech AWS HIPAA Compliance Assessment

## Project Summary

This project is a structured cloud security and compliance assessment of a healthcare AWS environment evaluated against the CSA Cloud Controls Matrix (CCM v4.0), HIPAA §164.312 technical safeguards, and AWS security best practices. The review covered identity and access management, data protection, logging, monitoring, and infrastructure segmentation. Evidence was gathered through configuration inspection, control mapping, and risk validation across approximately 20 control domains.

The assessment determined that the environment was only partially compliant (~60% control maturity) and exposed to significant regulatory and operational risk. Critical findings included a publicly accessible production database, unrestricted SSH access, root account without MFA, unencrypted and non-immutable PHI storage, and absence of real-time monitoring controls. The engagement resulted in a prioritized remediation roadmap spanning immediate identity hardening, encryption enforcement, logging enablement, and long-term architectural segmentation. The outcome translates technical misconfigurations into measurable HIPAA exposure and provides a clear path to defensible cloud security posture improvement.

---

## Repository Contents

- Full technical assessment with evidence and remediation mapping  
- Executive-level presentation summarizing risk posture and remediation strategy  
